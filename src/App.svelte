<script>

let value = '87';
function handleClick(val){
	value = val;
}

</script>

<!-- ATTENTION C'EST CLAIREMENT FAIT POUR 860px -->

<main>
	<img class="logo" src="build/logo.png" alt="decathlon" />

	<div class="middle">

		<div class="left">
			<img src="build/left.svg" alt="left" class="leftimg">

			<div class="left-content">
				<p class="orangeLine line-spacing">{value}%</p>
				<p class="bigLine line-spacing">de nos sportifs</p>
				<p class="bigLine line-spacing">sont satisfaits.</p>
				<p class="blueLine line-spacing">et vous ?</p>
				<p class="smallLine">Comme Charlotte nous espérons que chacun de nos sportifs continue d'être satisfait jour après jour.</p>
			</div>
			
		</div>

		<div class="right">
			<img src="build/right.svg" alt="right" class="rightimg">
			<div class="right-content">
				<p class="name">Charlotte, <span>le 10/02/2021</span></p>
				<p class="said">Merci aux personnes qui s'occupent de l'espace boxe. Me voici équipée, prête à gagner la médaille d'or aux jeux olympiques.</p>
				<img class="quote" src="build/quote.png" alt="quote"> 
			</div>
		</div>
	</div>

	<div class="smileys">
		
		<svg class="{value === '99' ? 'selected smiley five' : 'smiley five'}" width="32" height="33" fill="none" xmlns="http://www.w3.org/2000/svg" on:click={()=>handleClick('99')}>
  <path d="M8 13.55a1.714 1.714 0 103.429 0 1.714 1.714 0 00-3.429 0zm12.571 0a1.714 1.714 0 103.429 0 1.714 1.714 0 00-3.429 0zM16 .8C7.164.8 0 7.965 0 16.8c0 8.836 7.164 16 16 16s16-7.164 16-16c0-8.835-7.164-16-16-16zm9.393 25.393a13.29 13.29 0 01-4.225 2.85A13.153 13.153 0 0116 30.086a13.23 13.23 0 01-9.396-3.893 13.213 13.213 0 01-3.89-9.393 13.228 13.228 0 013.893-9.396A13.213 13.213 0 0116 3.514a13.228 13.228 0 019.396 3.893 13.212 13.212 0 013.89 9.393c0 1.797-.35 3.536-1.043 5.172a13.176 13.176 0 01-2.85 4.221zm-3.964-8.643H19.71a.288.288 0 00-.29.265 3.432 3.432 0 01-6.843 0 .288.288 0 00-.289-.265h-1.718a.287.287 0 00-.285.3A5.728 5.728 0 0016 23.265a5.728 5.728 0 005.714-5.415.286.286 0 00-.285-.3z" fill="#000"/>
</svg>
<svg class="{value === '87' ? 'selected smiley four' : 'smiley four'}" width="32" height="33" fill="none" xmlns="http://www.w3.org/2000/svg" on:click={()=>handleClick('87')}>
  <path d="M8 13.55a1.714 1.714 0 103.429 0 1.714 1.714 0 00-3.429 0zm12.571 0a1.714 1.714 0 103.429 0 1.714 1.714 0 00-3.429 0zM16 .8C7.164.8 0 7.965 0 16.8c0 8.836 7.164 16 16 16s16-7.164 16-16c0-8.835-7.164-16-16-16zm9.393 25.393a13.29 13.29 0 01-4.225 2.85A13.153 13.153 0 0116 30.086a13.23 13.23 0 01-9.396-3.893 13.213 13.213 0 01-3.89-9.393 13.228 13.228 0 013.893-9.396A13.213 13.213 0 0116 3.514a13.228 13.228 0 019.396 3.893 13.212 13.212 0 013.89 9.393c0 1.797-.35 3.536-1.043 5.172a13.176 13.176 0 01-2.85 4.221zm-3.964-8.643H19.71a.288.288 0 00-.29.265 3.432 3.432 0 01-6.843 0 .288.288 0 00-.289-.265h-1.718a.287.287 0 00-.285.3A5.728 5.728 0 0016 23.265a5.728 5.728 0 005.714-5.415.286.286 0 00-.285-.3z" fill="#000"/>
</svg>
<svg class="{value === '76' ? 'selected smiley three' : 'smiley three'}" width="32" height="33" fill="none" xmlns="http://www.w3.org/2000/svg" on:click={()=>handleClick('76')}>
  <path d="M8 13.55a1.714 1.714 0 103.429 0 1.714 1.714 0 00-3.429 0zm12.571 0a1.714 1.714 0 103.429 0 1.714 1.714 0 00-3.429 0zM16 .8C7.164.8 0 7.965 0 16.8c0 8.836 7.164 16 16 16s16-7.164 16-16c0-8.835-7.164-16-16-16zm9.393 25.393a13.29 13.29 0 01-4.225 2.85A13.153 13.153 0 0116 30.086a13.23 13.23 0 01-9.396-3.893 13.213 13.213 0 01-3.89-9.393 13.228 13.228 0 013.893-9.396A13.213 13.213 0 0116 3.514a13.228 13.228 0 019.396 3.893 13.212 13.212 0 013.89 9.393c0 1.797-.35 3.536-1.043 5.172a13.176 13.176 0 01-2.85 4.221zm-3.964-8.643H19.71a.288.288 0 00-.29.265 3.432 3.432 0 01-6.843 0 .288.288 0 00-.289-.265h-1.718a.287.287 0 00-.285.3A5.728 5.728 0 0016 23.265a5.728 5.728 0 005.714-5.415.286.286 0 00-.285-.3z" fill="#000"/>
</svg>
<svg class="{value === '45' ? 'selected smiley two' : 'smiley two'}" width="32" height="33" fill="none" xmlns="http://www.w3.org/2000/svg" on:click={()=>handleClick('45')}>
  <path d="M8 13.55a1.714 1.714 0 103.429 0 1.714 1.714 0 00-3.429 0zm12.571 0a1.714 1.714 0 103.429 0 1.714 1.714 0 00-3.429 0zM16 .8C7.164.8 0 7.965 0 16.8c0 8.836 7.164 16 16 16s16-7.164 16-16c0-8.835-7.164-16-16-16zm9.393 25.393a13.29 13.29 0 01-4.225 2.85A13.153 13.153 0 0116 30.086a13.23 13.23 0 01-9.396-3.893 13.213 13.213 0 01-3.89-9.393 13.228 13.228 0 013.893-9.396A13.213 13.213 0 0116 3.514a13.228 13.228 0 019.396 3.893 13.212 13.212 0 013.89 9.393c0 1.797-.35 3.536-1.043 5.172a13.176 13.176 0 01-2.85 4.221zm-3.964-8.643H19.71a.288.288 0 00-.29.265 3.432 3.432 0 01-6.843 0 .288.288 0 00-.289-.265h-1.718a.287.287 0 00-.285.3A5.728 5.728 0 0016 23.265a5.728 5.728 0 005.714-5.415.286.286 0 00-.285-.3z" fill="#000"/>
</svg>
<svg class="{value === '32' ? 'selected smiley one' : 'smiley one'}" width="32" height="33" fill="none" xmlns="http://www.w3.org/2000/svg" on:click={()=>handleClick('32')}>
  <path d="M8 13.55a1.714 1.714 0 103.429 0 1.714 1.714 0 00-3.429 0zm12.571 0a1.714 1.714 0 103.429 0 1.714 1.714 0 00-3.429 0zM16 .8C7.164.8 0 7.965 0 16.8c0 8.836 7.164 16 16 16s16-7.164 16-16c0-8.835-7.164-16-16-16zm9.393 25.393a13.29 13.29 0 01-4.225 2.85A13.153 13.153 0 0116 30.086a13.23 13.23 0 01-9.396-3.893 13.213 13.213 0 01-3.89-9.393 13.228 13.228 0 013.893-9.396A13.213 13.213 0 0116 3.514a13.228 13.228 0 019.396 3.893 13.212 13.212 0 013.89 9.393c0 1.797-.35 3.536-1.043 5.172a13.176 13.176 0 01-2.85 4.221zm-3.964-8.643H19.71a.288.288 0 00-.29.265 3.432 3.432 0 01-6.843 0 .288.288 0 00-.289-.265h-1.718a.287.287 0 00-.285.3A5.728 5.728 0 0016 23.265a5.728 5.728 0 005.714-5.415.286.286 0 00-.285-.3z" fill="#000"/>
</svg>
	</div>

	<div class="footer">
		<p class="miniTxt">*offre à durée limitée</p>
		<div class="bar"/>
	</div>

</main>

<style>
:global(body) {

	background: linear-gradient( -15deg, #fff 0%, #fff 40%, #E7F3F9 40%, #E7F3F9 60%);
	padding: 2rem;
	font-family: 'Roboto', arial, sans-serif;
	color: #001018;
	height: 100vh;
}
	main {
		/* padding: 2em; */
		max-width: 1200px;
		width: 100%;
		max-height: 100vh;
		margin: 0 auto;
	}
	.logo{
		height: 2rem;
		margin-bottom: 2rem;
	}

	.middle{
		display: grid;
		grid-template-columns: repeat(10, 1fr);
		grid-template-rows: repeat(5, 1fr);
		grid-column-gap: 0px;
		grid-row-gap: 0px; 
		height: 70vh;
overflow: hidden;
	}

	.left{
		/* width: 50%; */
		height: 100%;
		 grid-area:  1 / 1 / 2 / 6;
		position: relative;
		margin-left: -8px; /* petit cheat pour les ombres de mon svg */
		z-index: 9;
	}

	.leftimg{
		width:100%;
	}

	.left-content{
		position: absolute;
		top:0;
		left: 0;
		bottom: 0;
		right: 0;
		margin: auto;
		padding: 2rem;
		/* display: flex;
		flex-direction: column;
		justify-content: center;
		margin-bottom: 6rem; */
	}

.line-spacing{
	margin: 0;
	text-transform: uppercase;
}

.orangeLine{
color: #EB642B;
font-weight: bold;
font-size: 4rem;
font-style: italic;
}
.bigLine{
font-weight: bold;
font-size: 2rem;
font-style: italic;
}
.blueLine{
color: #4CA2D2;
font-weight: bold;
font-size: 2rem;
font-style: italic;
}
.smallLine{
font-size: 11px;
margin-top:2rem;
}


.right{
		margin-top: 2rem;
		/* width: 50%; */
		height: 100%;
		position: relative;
		margin-right: -8px; /* petit cheat pour les ombres de mon svg */
		/* transform: translateX(-40%); */
		grid-area:  1 / 5 / 2 / 11;
	}
	.right>img{
		width:100%;
	}

	.right-content{
		position: absolute;
left: 0;
bottom: 25%;
right: 0;
margin-left: 15%;
padding: 2rem 0 2rem 2rem;
width: 70%;
color: #fff;
font-size: 14px;
	}

	.name{
		font-weight: bold;
		font-size: 16px;
		margin: 0;
	}
	.name>span{
		font-weight: normal;
		font-size: 12px;
	}
.quote{
	position: absolute;
	bottom: 0;
	right: 0;
}

.smileys{
	display: flex;
	justify-content: center;
}
.smiley{
	margin: 0 .5rem;
	transition: all .4s;
}
.smiley:hover{
	transform: scale(1.3);
}
.selected{
	transform: scale(1.2) rotate(15deg);
}
.five>path{
	fill: green;
}
.four>path{
	fill: rgb(110, 182, 3);
}
.three>path{
	fill: rgb(233, 217, 74);
}
.two>path{
	fill: orange;
}
.one>path{
	fill: red;
}

.footer{
	position: fixed;
	bottom: 0;
	width:100vw;
	margin-left: -2rem;
}
.miniTxt{
	font-size: 12px;
	margin-left: 2rem;
}
.bar{
	height: 4px;
	background-color: #EB642B;
}


</style>