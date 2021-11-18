<nav>
	<ul sveltekit:prefetch class="nav">
		<li>
			<a  href="/">Home</a>
		</li>
		<li>
			<a href="/menu">Menu</a>
		</li>
		<li>
			<a href="/events">Events</a>
		</li>
		<li>
			<a href="/contact">Contact</a>
		</li>
		<li>
			<a href="tel:+13603778516">Call now!</a>
		</li>
	</ul>
	<p> <a href="tel:+13603778516">(360) 377-8516</a> <br> <a href="https://www.google.com/maps/place/Cloverleaf+Sports+Bar+%26+Grill/@47.6028616,-122.6301326,17z/data=!3m2!4b1!5s0x549039f471ba5523:0x8a5eaeffbcde7830!4m5!3m4!1s0x549039f47759a169:0xc093d466b16733ce!8m2!3d47.602858!4d-122.6279439"> 1240 Hollis Street, Bremerton, WA 98310 </a></p>
</nav>

<style lang="scss">

	@import 'vari';
	
	@mixin nav() {
    position: fixed;
    bottom: -80px;
    right: 0;
    transform: translateY(-50%);
    z-index: 4;
    font-weight: bold;
    
    li {
        list-style: none;

        a {
            display: block;
            text-decoration: none;
            text-shadow: none;
            background: rgba(255, 255, 244, 0.733);
            color: $backgroundMain;
            height: 30px;
            line-height: 30px;
            font-size: 2vmax;
            width: 10vmax;
            margin: 3px 0;
            padding:0 15px;
            border-top-left-radius: 5px;
            border-bottom-left-radius: 5px;

            &:hover {
                transition: 0.2s;
                background: $clover;
                color: $backgroundMain;
				box-shadow:5px 0px 25px #ffffbd73;
            }
        }
    }

}



.nav {

    @include nav();


}

p {
	margin-left: 4%;
	
	a{
		text-decoration: none;
		color: $textColorMain;
	}
	
}
	
	//
	//ul {
	//	display: flex;
	//	list-style: none;
	//	margin: 0;
	//	font-size: 2vw;
	//	padding: 0 35%;
	//	align-items: right;
	//	
	//	li {
	//	margin:0 7px;
	//	border-style: none solid solid solid;
	//	border-color:rgb(255, 255, 244);
  	//	border-width: 2px;
	//	border-radius:0 0 5px 5px;
	//	letter-spacing: 0.1vw;
	//	padding: 0 4px;
	//	
	//	&:hover{
	//		background-color:#39993b09;
	//		transition: 0.3sec;
	//		box-shadow:11px 12px 100px #39993b7a;
	//	}
	//		
	//	a{
	//		color: #39993A;
	//		text-decoration: none;
	//		background-color: transparent;
	//		&:hover{
	//			transition: 0.3sec;
	//			color: rgb(208, 231, 78);
	//		}
	//	}
	//}
	//}


</style>
