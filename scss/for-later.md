SASS pour inclure l'icon correspondant au réseau social :
```
.social-links {
	@each $sm in $social-links {
		.icon-#{$sm} {
			background-image: url("img/#{$sm}.png");
		}
	}
}
```