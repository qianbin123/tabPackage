<script>
export default {
    name:"Mycomponent",
    data(){
        return{
            
        }
    },
    render(){
        return(
            <div>
                {this.$slots.default}
            </div>
        )
    }
}
</script>

<style lang="css" scoped>

</style>
