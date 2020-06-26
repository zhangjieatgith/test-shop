<template>
    <div>
        <header-top title="首页标题，南京市高淳区">
            <span slot="left">
                searchBtn
            </span>
            <span slot="right">
                loginBtn
            </span>
        </header-top>
        Msite
    </div>
</template>
<script>
import HeaderTop from '@/components/HeaderTop/HeaderTop'
import Swiper from 'swiper'
import 'swiper/css/swiper.min.css'

export default {
    components: {
        HeaderTop
    }
}
</script>
<style scoped>

</style>