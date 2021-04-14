<template>
	<footer class="footer">
		<div class="minmax">
			<div class="footer__content">
				<div class="footer__top">
					<div class="col">
						<div class="col__head">
							<a
								href="https://www.hiretrades.com.au/"
								title="HIREtrades Logo"
							>
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
							</a>
						</div>

						<div class="hr"></div>

						<h1 class="col__body">
							Australia's most trusted trades provider
						</h1>
					</div>

					<div class="col">
						<h2 class="col__head">Customers</h2>

						<div class="hr"></div>

						<ul class="col__links">
							<li>
								<a href="https://getquotes.hiretrades.com.au/">
									Get Qoutes</a
								>
							</li>

							<li>
								<a href="https://www.hiretrades.com.au/trades">
									200+ Trades
								</a>
							</li>

							<li>
								<a
									href="https://www.hiretrades.com.au/how-it-works-customer"
								>
									How it Works
								</a>
							</li>

							<li>
								<a
									href="https://www.hiretrades.com.au/trades-directory"
								>
									Trades Directory
								</a>
							</li>

							<li>
								<a href="https://www.hiretrades.com.au/faq-customer">
									FAQs
								</a>
							</li>
						</ul>
					</div>

					<div class="col">
						<h2 class="col__head">Tradies</h2>

						<div class="hr"></div>

						<ul class="col__links">
							<li>
								<a href="https://register.hiretrades.com.au/">
									Register
								</a>
							</li>

							<li>
								<a href="https://www.hiretrades.com.au/account/#/login">
									Login
								</a>
							</li>

							<li>
								<a
									href="https://www.hiretrades.com.au/how-it-works-business"
								>
									How it Works
								</a>
							</li>

							<li>
								<a href="https://www.hiretrades.com.au/faq-business">
									FAQs
								</a>
							</li>
						</ul>
					</div>

					<div class="col">
						<h2 class="col__head">HIREtrades</h2>

						<div class="hr"></div>

						<ul class="col__links">
							<li>
								<a href="https://www.hiretrades.com.au/contact-us">
									Contact Us
								</a>
							</li>

							<li>
								<a href="https://www.hiretrades.com.au/our-story">
									Our Story
								</a>
							</li>

							<li>
								<a
									href="https://www.hiretrades.com.au/terms-conditions"
								>
									Terms & Conditions
								</a>
							</li>

							<li>
								<a href="https://www.hiretrades.com.au/blog">
									Blogs
								</a>
							</li>

							<li>
								<a href="https://www.hiretrades.com.au/cost-guides">
									Cost Guides
								</a>
							</li>
						</ul>
					</div>

					<div class="col">
						<div class="col__dl">
							<h2 class="col__head">Download our apps</h2>

							<div class="hr"></div>

							<div class="ios__android">
								<a
									href="https://apps.apple.com/au/app/id1311963554"
									target="_blank"
									rel="noreferrer"
									class="ios"
								>
									<img src="../assets/ios-black.png" alt="ios" />
								</a>

								<a
									href="https://play.google.com/store/apps/details?id=io.htmobile.app&hl=en"
									target="_blank"
									rel="noreferrer"
									class="android"
								>
									<img
										src="../assets/android-black.png"
										alt="android"
									/>
								</a>
							</div>
						</div>

						<div class="col__follow">
							<h2 class="col__head">Follow us</h2>

							<div class="hr"></div>

							<div class="col__icns">
								<a href="https://www.facebook.com/HireTradesAustralia/">
									<i class="fab fa-facebook-f"></i>
								</a>

								<a href="https://twitter.com/HIREtradesAU">
									<i class="fab fa-twitter"></i>
								</a>

								<a href="https://www.instagram.com/hiretrades/">
									<i class="fab fa-instagram"></i>
								</a>

								<a
									href="https://www.pinterest.com.au/hiretradesaustralia/_created/"
								>
									<i class="fab fa-pinterest"></i>
								</a>

								<a
									href="https://www.linkedin.com/company/hiretrades/about/"
								>
									<i class="fab fa-linkedin-in"></i>
								</a>
							</div>
						</div>
					</div>
				</div>

				<div class="divider"></div>

				<div class="footer__btm">
					<p class="scale__block">
						&copy; 2021 -
						<a href="https://www.hiretrades.com.au/"
							>www.HIREtrades.com.au</a
						>
						| All Rights Reserved
					</p>

					<div class="scale__none">
						<p>&copy; 2020 - www.HIREtrades.com.au</p>
						<p>All Rights Reserved</p>
					</div>

					<div class="privacy">
						<a
							href="https://www.hiretrades.com.au/privacy-policy"
							class="pp__scale"
						>
							Privacy Policy</a
						>

						<a
							href="https://www.hiretrades.com.au/privacy-policy"
							class="pp"
						>
							Privacy Policy
						</a>

						<span class="pipe">|</span>

						<a href="https://www.hiretrades.com.au/sitemap" class="mp"
							>Sitemap</a
						>

						<span class="pipe">|</span>

						<span>v_2.0.78</span>
					</div>
				</div>
			</div>
		</div>
	</footer>
</template>

<script>
export default {
	name: 'Footer'
};
</script>

<style lang="scss" scoped>
.footer {
	background-color: #e6eaee;
	padding: 2.5rem 0 1rem;

	&__top {
		display: grid;
		grid-template-columns: auto 185px 185px 185px auto;
		grid-gap: 15px;

		.col {
			&__head {
				font-size: 1.3rem;
				font-weight: 400;
				line-height: 1.2;
				color: #475f7b;

				a {
					display: flex;
					align-items: center;

					.ht__text {
						margin-left: 13px;
					}
				}
			}

			.hr {
				background-color: #bfbfbf;
				height: 0.3px;
				width: 25%;
				margin: 15px 0;
			}

			&__body {
				font-size: 1.47rem;
				font-weight: 400;
				line-height: 1.2;
				color: #475f7b;
			}

			&__links {
				li {
					list-style-type: none;
					line-height: 28px;
					margin-bottom: 5px;

					a {
						color: #727e8c;
						text-decoration: none;

						&:hover {
							text-decoration: underline;
							color: #7367f0;
						}
					}
				}
			}

			&__dl {
				.ios__android {
					display: flex;
					justify-content: space-between;
					margin-bottom: 3rem;

					.ios {
						margin-right: 15px;
					}
				}
			}

			&__follow {
				.col__icns {
					a {
						i {
							color: #475f7b;
							margin: 5px 8px;
						}

						&:hover {
							i {
								color: #7367f0;
							}
						}
					}
				}
			}
		}
	}

	.divider {
		background-color: #bfbfbf;
		height: 0.3px;
		width: 25%;
		margin: 3rem 0 15px;
	}

	&__btm {
		display: flex;
		align-items: center;
		justify-content: space-between;

		p {
			color: #666;
			font-size: 13px;
			user-select: none;

			a {
				color: #666;
				text-decoration: none;
			}
		}

		.scale__none {
			display: none;
		}

		.privacy {
			.pp__scale {
				display: none;
			}

			a {
				font-size: 13px;
				color: #727e8c;
				text-decoration: none;

				&:hover {
					color: #7367f0;
					border-bottom: 1px solid #7367f0;
				}
			}

			.pipe {
				margin: 0 8px;
			}

			span {
				font-size: 13px;
				color: #727e8c;
			}
		}
	}
}

@media screen and (max-width: 1220px) {
	.footer {
		&__top {
			grid-template-columns: auto 160px 160px 160px auto;
		}
	}
}

@media screen and (max-width: 1194px) {
	.footer {
		&__top {
			grid-template-columns: auto 130px 130px 130px auto;
			grid-gap: 30px;
		}
	}
}

@media screen and (max-width: 991px) {
	.footer {
		&__top {
			grid-template-columns: repeat(4, 1fr);

			.col {
				&__dl {
					.ios__android {
						display: flex;
						flex-direction: column;
						margin-bottom: 3rem;

						.ios {
							margin-right: 0;
							margin-bottom: 15px;
						}
					}
				}
			}

			.col:nth-of-type(1) {
				display: none;
			}
		}

		&__btm {
			.scale__block {
				display: none;
			}

			.scale__none {
				display: block;

				p {
					font-size: 1rem;
					margin-bottom: 15px;
				}
			}
		}
	}
}

@media screen and (max-width: 992px) {
	.footer {
		&__top {
			grid-template-columns: repeat(3, 1fr);
			grid-gap: 50px 15px;
		}
	}
}

@media screen and (max-width: 767px) {
	.footer {
		&__top {
			grid-template-columns: repeat(3, 1fr);
			grid-gap: 50px 15px;
		}

		.divider {
			margin: 3rem auto 15px;
		}

		&__btm {
			flex-direction: column;
			text-align: center;

			.privacy {
				margin: 30px 0;

				.pp__scale {
					display: block;
					font-size: 1rem;
				}

				.pp,
				.mp,
				span {
					display: none;
				}
			}
		}
	}
}

@media screen and (max-width: 575px) {
	.footer {
		&__top {
			display: flex;
			flex-direction: column;
			align-items: center;
			text-align: center;

			.col {
				.hr {
					margin: 15px auto;
				}
			}
		}
	}
}
</style>
