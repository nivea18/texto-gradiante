@supports (background-clip: text) or (-webkit-background-clip: text) {
    .gradient-text {
        font-size: 3rem; /* ajuste como quiser */
        font-weight: bold;
        background-image: linear-gradient(
            to right,
            #ba1d6c,
            #db3f56,
            #8a0077,
            #ff81ee,
            #ff8bbb,
            #bf0050,
            #ff0084,
            #eb8dbd,
            #e60077
        );
        -webkit-background-clip: text; /* Chrome, Edge, Safari */
        background-clip: text;         /* Firefox moderno */
        -webkit-text-fill-color: transparent; /* Chrome, Edge, Safari */
        color: transparent;             /* fallback para todos */
    }
}
