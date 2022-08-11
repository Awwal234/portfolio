<svelte:head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no">
    <link rel="stylesheet" href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css">
    <title>Dolapo Portfolio | Contact</title>
</svelte:head>

<script>
    import '../app.css';
</script>

<body class="text-white p-[20px] bg-[#111827]">
    <div class="mx-auto md:w-[50%] w-[90%] mt-[10%]" id="name">
        <div class="text-left">
            <span class="font-bold text-[25px] md:text-[30px]">Contact me</span>
            <form action="https://formspree.io/f/mrgjawnn"
            method="post">
                <input type="text" name="name" placeholder="Your name" class="w-full bg-transparent rounded-md border border-white mt-[20px] p-[10px]">
                <input type="email" name="_replyto" placeholder="Your email" class="w-full bg-transparent rounded-md border border-white mt-[20px] p-[10px]">
                <textarea name="message" placeholder="Enter your message here" class="w-full bg-transparent rounded-md border border-white mt-[20px] p-[10px]"></textarea>
                <input type="hidden" name="_subject" value="Contact form submitted" class="w-full bg-transparent rounded-md p-[10px]">
                <button type="submit" class="bg-indigo-800 py-[10px] px-[20px] rounded-md text-white font-bold mt-[20px] hover:opacity-90 shadow-sm shadow-slate-700">
                    Submit
                </button>
            </form>
            <div class="mt-[20px]">
                <i class="las la-arrow-circle-left"></i>
                <a href="/">Home Page</a>
            </div>
        </div>
    </div>
</body>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Josefin+Sans&family=Roboto&family=Rubik+Dirt&display=swap');
    #name{
        font-family: 'Roboto', sans-serif;
    }
    input:focus{
        outline:none;
    }
</style>