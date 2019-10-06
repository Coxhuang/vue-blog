<template>
	<div class="home-main">
		<div class="home-main-box">
			<div class="home-main-content">
				<div class="home-main-content-media">
					<a class="home-main-content-media-left">
						<img src="https://cdn.pigjian.com/cover/2018/10/11/mzcJBgfUXAJWC7E4YOqcysOP4L7vXvadI71nSCtS.jpg" alt="">
					</a>
					<div class="home-main-content-media-right">
						<div class="media-right-title">
							<a href="https://www.pigjian.com/article/ubuntu-1604-installation-deployment-environment">
								Ubuntu 16.04 环境安装部署
							</a>
						</div>
						<div class="media-right-meta">
							<span class="media-right-meta-cinema">
								项目部署文档
							</span>
						</div>
						<div class="media-right-extra">
							<a href="https://www.pigjian.com/tag/%E5%85%A5%E9%97%A8">
								<div class="media-right-extra-label">
									<i class="el-icon-s-flag">
									</i>
									入门
								</div>
							</a>
							<div class="media-right-extra-info">
								<i class="el-icon-user-solid"></i>
								Jiajian , 
								<i class="el-icon-timer"></i>
								11个月前 , 
								<i class="el-icon-view"></i>
								4930
								<a class="pull-right" href="https://www.pigjian.com/article/ubuntu-1604-installation-deployment-environment">
									Read More 
									<i class="el-icon-more"></i>
								</a>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
	name: 'HomeMain',
		data () {
			return {
				msg: 'Welcome to Your Vue.js App'
			}
		}
	}
</script>

<style lang="scss" scoped>
	.home-main{
		width: 100%;
		height: auto;
		margin: 30px 0 0 0;
		padding: 0;
		.home-main-box{
			width: 81.25%;
			height: 100%;
			padding: 0 15px;
			margin: 0 auto;
			.home-main-content{
				width:100%;
				height: 100%;
				padding: 0;
				margin: 0;
				.home-main-content-media{
					width: 100%;
					height: auto;
					margin: 30px 0 0 0;
					padding: 0 0 28px 0;
					.home-main-content-media-left{
						display: inline-block;
						height: 100%;
						width: auto;
						padding: 0 10px 0 0;
						img{
							height: 100%;
							width: 260px;
							margin: 0;
							padding: 0;
						}
					};
					.home-main-content-media-right{
						display: inline-block;
						height: 100%;
						width: 508px;
						padding: 0;
					}
				}
			}
		}
	}
</style>
