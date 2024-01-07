Type: File
Content-Type: text/css
Title: Stylesheet
Location: /style.css

:root {
    --background: #f4eed7ff;
    --default-size: 1em;
    --header-font: 'Caladea', serif;
    --default-font: 'Lato', sans-serif;
    --default-c: #171717;
}


body {
    max-width: 40em;
    margin: auto;
    font-family: var(--default-font);
    font-size: var(--default-size);
    padding: 0;
    background-color: var(--background);
    color: var(--default-c);
    transition: all 0.2s ease-in-out;
    }

    h1, h2, h3, h4, h5, h6 {
        font-family: var(--header-font);
        padding: 0;
        margin: 0;
    }

        h1 {
            font-size: 4rem;
            line-height: 4rem;
        }

        h2 {
            font-size: 3rem;
        }

        h3 {
            font-size: 2rem;
        }

        h4 {
            font-size: 1.8rem;
        }

        h5 {
            font-size: 1rem;
        }

    a {
        color: #222;
    }
     a:hover {
        background-color: #7BDCB5;
        border-bottom: 1px solid #444;
        transition: all 0.2s ease-in-out;
     }


    @media (max-width: 500px) {
	body {
		font-size: 0.9em;
	}
    main {
        line-height: 1rem !important;
    }
    h1 {
        font-size: 2rem;
        line-height: 2rem;
    }
    h2 {
        font-size: 1.5rem;
    }
    .top-right a {
        padding: 0.3rem !important;
        font-size: 0.6rem !important;
    }
}


/* special divs ----------------- */

    .outline {
        border: 1px solid #000;
        width: fit-content;
        margin-bottom: 2rem;
    }

    .black {
        padding: 2rem;
        padding-bottom: 3rem;
        background-color: #000;
        color: var(--background);
    }

    .black a {
        color: var(--background) !important;
        border-bottom: 1px solid var(--background);
    }

    .img {
        text-align: center;
        font-size: 0.8rem;
        font-style: italic;
        line-height: 1rem;
    }

    .img img {
        max-width: 100%;
    }


/* navigation ------------------------- */

.top {
	min-height: fit-content;
	background-color: var(--background);
	width: 100%;
    margin: 0, auto;
    letter-spacing: 0.1rem;
}
    .top-container {
        display: flex;
        border: 1px solid #000;
    }

	.top-left {
		flex: 1;
		flex-grow: 1;
        padding: 1rem;
        border-right: 1px solid #000;
        text-align: center;
	}

	.top-right {
		flex: 2;
        flex-grow: 8;
        align-self: center;
        text-align: center;
	}

	.top-right ul {
	    list-style-type: none;
	    text-align: right;
	}

	.top-right li {
	    display: inline-flex;
    }

    .top-right a {
        text-decoration: none;
        padding: 0.5rem;
        font-size: 0.8rem;
    }

/* header ----------------------- */

.header {
    border-left: 1px solid #000;
    border-right: 1px solid #000;
    background-image: url("https://i.postimg.cc/TPtygz2P/diskssm.png");
    background-size: cover;
    background-repeat: no-repeat;
    min-height: 20em;
    color: transparent;
}
    .header img {
        width: 100%;
        height: auto;
}

main {
    border-left: 1px solid #000;
    border-right: 1px solid #000;
    background-color: #bee5a3;
    padding-top: 3rem;
    padding-bottom: 3em;
    padding-left: 1em;
    padding-right: 1em;
    border-bottom: 1px solid #000;
    line-height: 2rem;
}

.post-info {
    font-size: 0.8rem;
    padding: 0.5rem;
    margin: 0rem;
    line-height: 1rem;
}

hr {
    height: 1px;
    border: 0;
    margin-top: 1rem;
    margin-bottom: 1rem;
    border-bottom: 1px solid #000;
}

footer {
        max-width: 100%;
        background-color: rgb(66, 196, 170);
        padding: 1em;
        text-align: center;
        font-size: 0.8rem;
        border-left: 1px solid #000;
        border-right: 1px solid #000;
    }


    .profile-picture {
        width: 10em;
        border-radius: 60em;
    }