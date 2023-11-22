<div class="text">
    <div>L</div>
    <div>o</div>
    <div>r</div>
    <div>e</div>
    <div>m</div>
</div>

<style>
    @font-face {
        font-family: "Open Sans Hebrew";
        src: url("/OpenSans-Regular.ttf");
    }

    .text {
        font-family: "Open Sans Hebrew";
        font-size: 10rem;
        display: flex;

        & > div {
            border-top: 5px solid coral;
            border-bottom: 5px solid darkblue;
            border-left: 5px solid darkgreen;
            border-right: 5px solid goldenrod;

            padding: 0.5rem 1rem;
            margin: 0 0.5rem;
        }

        /*& > div {*/
        /*    width: fit-content;*/
        /*    background-clip: text;*/
        /*    -webkit-background-clip: text;*/

        /*    -webkit-text-fill-color: transparent;*/
        /*    background-image: url("/64691BB5-02B7-4ACA-BD2E-645532A9D93D.png");*/
        /*    background-size: 100% 100%;*/
        /*}*/
    }
</style>
