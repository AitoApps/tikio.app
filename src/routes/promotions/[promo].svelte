<script context="module">
    export const load = ({ URL, params }) => {
        console.log(params);
        let promo = params.offer;

        return {
            props: {
                promo,
            },
        };
    };
</script>

<script>
    export let promo;
</script>

<h1>{promo}</h1>
