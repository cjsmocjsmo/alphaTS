<script>
    import kitsap from '$lib/images/kitsap.webp'
    import mason from '$lib/images/mason.webp';
    import pierce from '$lib/images/pierce.webp';
</script>



<div class='mainDiv'>
	<section class="sec">
		<p class="teleNum">360 516 8933</p>
		<p class="atsServ">Servicing</p>
		<div class="cardDiv">
			<div class="card">
				<div class="card-body">
					<h1 class="card-title">Kitsap County</h1>
                    

					<div>
						<img class="cardImg" src={kitsap} alt="Placeholder image">
					</div>
				</div>
			</div>
			<div class="card">
				<div class="card-body">
					<h1 class="card-title">Mason County</h1>
					<div>
						<img class="cardImg" src={mason} alt="Placeholder image">
					</div>
				</div>
			</div>
			<div class="card">
				<div class="card-body">
					<h1 class="card-title">Pierce County</h1>
					<div>
						<img class="cardImg" src={pierce} alt="Placeholder image">
					</div>
				</div>
			</div>
		</div>
		<div class="gallery">
			<a href="https://alphatreeservicegallery.pages.dev" >
				<p class="p-gallery">Photo Gallery</p>
			</a>
			<a href="https://alphatreeservicevids.pages.dev" >
				<p class="p-gallery">Video Gallery</p>
			</a>
		</div>
		<br>
	</section>
</div>

<style>
    .mainDiv {
        margin-top: 1.5em;
        width: 100%;
    }

    .sec {
        background-color: rgb(6, 40, 134);
        border: 4px solid yellowgreen;
        border-radius: 10px;
    }

    .teleNum {
        margin-top: 0.5em;
        text-align: center;
        font-size: 5em;
        font-weight: 900;
        color: antiquewhite;
    }

    .atsServ {
        text-align: center;
        font-size: 4.5em;
        color: antiquewhite;
    }

    .cardDiv {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-evenly;
    }

    .card-title {
        color: antiquewhite;
        text-align: center;
    }

    /* .card {
        width: 25em;
    } */

    .cardImg {
        border-radius: 8px;
        width: 100%;
    }

    div.gallery {
        margin-top: 1.5em;
        margin-bottom: 2.5em;
    }

    p.p-gallery {
        color: antiquewhite;
        text-align: center;
        font-size: 3em;
    }


    /* @media (max-width: 2010px) {
        .mainDiv {
            margin-top: 94vh;
        }
        .teleNum {
            margin-top: 0.5em;
            text-align: center;
            font-size: 4.5em;
            font-weight: 900;
            color: antiquewhite;
        }

        .atsServ {
            text-align: center;
            font-size: 2.75em;
            color: antiquewhite;
        }

        .card {
            width: 17em;
        }

    }

    @media (max-width: 1810px) {
        .teleNum {
            margin-top: 0.5em;
            text-align: center;
            font-size: 4.5em;
            font-weight: 900;
            color: antiquewhite;
        }

        .atsServ {
            text-align: center;
            font-size: 2.75em;
            color: antiquewhite;
        }

        .card {
            width: 17em;
        }

    }

    @media (max-width: 1510px) {
        .mainDiv {
            margin-top: 89vh;
        }

        .teleNum {
            margin-top: 0.5em;
            text-align: center;
            font-size: 5.5em;
            font-weight: 900;
            color: antiquewhite;
        }

        .atsServ {
            text-align: center;
            font-size: 3.75em;
            color: antiquewhite;
        }

        .card {
            width: 12em;
        }
    }

    @media (max-width: 1310px) {
        .mainDiv {
            margin-top: 90vh;
        }

        .teleNum {
            margin-top: 0.5em;
            text-align: center;
            font-size: 5.5em;
            font-weight: 900;
            color: antiquewhite;
        }

        .atsServ {
            text-align: center;
            font-size: 3.75em;
            color: antiquewhite;
        }

        .card {
            width: 12em;
        }
    }

    @media (max-width: 1200px) {
        .mainDiv {
            margin-top: 102vh;
        }
    }

    @media (max-width: 1010px) {
        .mainDiv {
            margin-top: 75vh;
        }
    }

    @media (max-width: 769px) {
        .mainDiv {
            margin-top: 73vh;
            margin-bottom: 2em;
        }

        .teleNum {
            margin-top: 0.5em;
            text-align: center;
            font-size: 4em;
            font-weight: 900;
            color: antiquewhite;
            font-size: 2.75em;
        }

        .atsServ {
            text-align: center;
            font-size: 2.2em;
            color: antiquewhite;
        }

        p.p-gallery {
            color: antiquewhite;
            text-align: center;
            font-size: 2.2em;
        }
    }

    @media (max-width: 650px) {
        .mainDiv {
            margin-top: 49vh;
        }
    }
*/
    /* @media (max-width: 540px) {
        /* .mainDiv {
            margin-top: 0.25vh;
            margin-bottom: 2em;
        } */

        /* .sec {
            background-color: rgb(6, 40, 134);
            margin-top: 17em;
            border: 4px solid yellowgreen;
            border-radius: 10px;
        } */

        /* .cardDiv {
            flex-direction: column;
            height: fit-content;
        } */
    /* } */

    /* @media (max-width: 412px) { */
        /* .mainDiv {
            margin-top: 1em;
            margin-bottom: 2em;
        } */

        /* .teleNum {
            margin-top: 0.5em;
            text-align: center;
            font-size: 2em;
            font-weight: 900;
            color: antiquewhite;
        } */

        /* p.p-gallery {
            color: antiquewhite;
            text-align: center;
            font-size: 1em;
        } */
    /* }  */

    @media (max-width: 375px) {
        .teleNum {
            margin-top: 0.5em;
            text-align: center;
            font-size: 2em;
            font-weight: 900;
            color: antiquewhite;
        }
        .atsServ {
            text-align: center;
            font-size: 1.85em;
            color: antiquewhite;
        }
        /* p.p-gallery {
            color: antiquewhite;
            text-align: center;
            font-size: 1.2em;
        } */
        .cardDiv {
            flex-direction: column;
        }
        .cardImg {
            width: 200px;
            
        } 
    }
</style>