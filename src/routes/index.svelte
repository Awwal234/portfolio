<svelte:head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no">
    <link rel="stylesheet" href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css">
    <title>Dolapo Portfolio</title>
</svelte:head>

<script>
	import '../app.css';
    import Header from '../components/header.svelte';
    import Herosection from '../components/herosection.svelte';
    import Project from '../components/project.svelte';
    import Quote from '../components/quote.svelte';
    import Footer from '../components/footer.svelte';
</script>

<body class="bg-[#111827] text-white">
    <Header/>
    <Herosection/>
    <Project/>
    <Quote/>
    <Footer/>
</body>
