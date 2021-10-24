<script>
    import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';
    import Footer from '$lib/Footer.svelte';

    let myInfo = {
    title: "Info",
    item1: "Lee Yee Kang",
    item2: 16,
    item3: "Han Chiang High School",
    hobby1: "Listening to Music",
    hobby2: "Playing Video Games",
    hobby3: "Watching Anime",
    personality1: "Cool",
    personality2: "Quiet",
    personality3: "Shy"
}

</script>
    <Header title={"My Biography"} />

    <Section {...myInfo} />

    <Footer gitHub={"https://github.com/yklee7285?tab=repositories"} />




