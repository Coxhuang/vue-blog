<template>
	<div class="home-title">
        <!-- 标题 -->
		<div class="home-title-box">
        <!-- 标题-盒子 -->
            <div class="home-title-content">
            <!-- 标题-内容 -->
                <h3>Nothing is impossible.</h3>
                <h6>https://pigjian.com</h6>
            </div>
	    </div>
	</div>
</template>

<script>

	export default {
	name: 'HomeTitle',
		data () {
			return {
				msg: 'Welcome to Your Vue.js App'
			}
		}
	}
</script>

<style lang="scss" scoped>
	.home-title{
        width: 100%;
        min-height: 218px;
        background-color: #9caebf;
        .home-title-box{
            width: 100%;
            min-height: 218px;
            margin: 0 0 0 0;
            padding: 30px 60px 50px 60px;
            .home-title-content{
                width: 100%;
                min-height: 108px;
                margin: 0;
                padding: 0 15px;
                h3 {
                    display: block;
                    width: 100%;
                    height: 38px;
                    margin: 24px 0;
                    padding: 0;
                    font-size: 32px;
                    font-weight: 400;
                    color: #fff;
                    line-height: 1.2;
                    font-family: lato-regular,"Helvetica Neue",Helvetica,Arial,"Hiragino Sans GB","Microsoft YaHei",sans-serif;
                    text-align: center;
                }
                h6 {
                    display: block;
                    width: 100%;
                    height: 22px;
                    margin: 12px 0;
                    padding: 0;
                    font-size: 19px;
                    font-weight: 400;
                    color: #fff;
                    line-height: 1.2;
                    font-family: lato-regular,"Helvetica Neue",Helvetica,Arial,"Hiragino Sans GB","Microsoft YaHei",sans-serif;
                    text-align: center;
                }
            }
        }
    }
</style>
