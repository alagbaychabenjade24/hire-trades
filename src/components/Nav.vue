<template>
	<div class="nav">
		<div class="nav__logo">
			<img
				src="../assets/logo-ht-icon.png"
				alt="ht logo icon"
				class="ht__icn"
			/>
			<img
				src="../assets/logo-ht-text.png"
				alt="ht logo text"
				class="ht__text"
			/>
		</div>

		<div class="nav__links">
			<ul class="links__left">
				<li><a href="https://www.hiretrades.com.au/">Trades</a></li>

				<li>
					<a
						href="https://www.hiretrades.com.au/cost-guides"
						target="_blank"
						rel="noreferrer"
					>
						Cost Guides
					</a>
				</li>

				<li>
					<a
						href="https://www.hiretrades.com.au/blog"
						target="_blank"
						rel="noreferrer"
					>
						Blogs
					</a>
				</li>
			</ul>

			<ul class="links__right">
				<li>
					<a
						href="https://www.hiretrades.com.au/"
						target="_blank"
						rel="noreferrer"
					>
						Get Quotes
					</a>
				</li>

				<li>
					<button>Register Business</button>
				</li>

				<li>
					<a
						href="https://www.hiretrades.com.au/account/#/login"
						target="_blank"
						rel="noreferrer"
					>
						Login
					</a>
				</li>
			</ul>
		</div>

		<div class="nav__menu">
			<div class="line"></div>
			<div class="line"></div>
			<div class="line"></div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'Nav'
};
</script>

<style lang="scss" scoped>
.nav {
	position: fixed;
	top: 0;
	display: flex;
	align-items: center;
	background-color: white;
	border-bottom: 1px solid #dfe3e7;
	height: 60px;
	width: 100%;
	padding: 0 1rem;
	z-index: 9999;

	&__logo {
		display: flex;
		align-items: center;
		margin-right: 55px;

		.ht__text {
			margin-left: 13px;
		}
	}

	&__links {
		display: flex;
		justify-content: space-between;
		width: 100%;

		.links__left,
		.links__right {
			display: flex;
			align-items: center;

			li {
				list-style-type: none;
				font-weight: 600;
				color: #666;

				a {
					font-weight: 600;
					color: #666;
					text-decoration: none;
					padding: 1rem 1.125rem;

					&:hover {
						color: #7367f0;
						border-bottom: 2px solid #7367f0;
					}
				}

				button {
					font-size: 15px;
					color: #7367f0;
					background-color: white;
					border: 1px solid #7367f0;
					border-radius: 0.267rem;
					padding: 9px 22px;
					margin: 0 13px;
					cursor: pointer;
					transition: 0.2s ease;

					&:hover {
						color: white;
						background-color: #7367f0;
					}
				}
			}
		}
	}

	&__menu {
		display: none;
		cursor: pointer;

		.line {
			background-color: rgb(51, 51, 51);
			height: 2px;
			width: 25px;
		}

		.line:nth-of-type(2) {
			margin: 5px 0;
		}
	}
}

@media screen and (max-width: 991px) {
	.nav {
		display: flex;
		justify-content: space-between;
		padding: 1rem;

		&__links {
			position: absolute;
			top: 60px;
			left: 0;
			display: flex;
			flex-direction: column;
			background-color: white;
			padding: 20px;
			z-index: -9;
			transform: translateY(-120%);

			.links__left,
			.links__right {
				display: flex;
				flex-direction: column;
				align-items: flex-start;

				li {
					padding: 15px 0;

					a {
						text-decoration: none;
						padding: 0;
					}

					button {
						font-size: 1rem;
						border: none;
						cursor: pointer;
						font-weight: 600;
						color: #666;
						text-decoration: none;
						padding: 0;
						margin: 0;

						&:hover {
							color: #7367f0;
							background-color: white;
							border-bottom: 2px solid #7367f0;
						}
					}
				}
			}
		}

		&__menu {
			display: block;
		}
	}
}
</style>
