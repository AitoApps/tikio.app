<script context="module">
    export const load = ({ URL, params }) => {
        console.log(params);
        let offer = params.offer;

        return {
            props: {
                offer,
            },
        };
    };
</script>

<script>
    export let offer;
</script>

<h1>{offer}</h1>
