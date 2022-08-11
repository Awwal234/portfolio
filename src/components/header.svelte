<script>
    import '../app.css'
</script>

<header class="bg-[#111827] items-center w-full flex fixed p-[20px] top-0 justify-between shadow-sm shadow-gray-800">
    <div class="text-white font-bold text-[20px]" id="logo">
        <span>
            DTheDev
        </span>
    </div>
    <!--all about the home, about-->
    <div class="hidden md:hidden lg:flex" id="list">
        <ul class="flex space-x-[40px] text-white text-[16px] font-normal" id="lsty">
            <li><a href="/">Home</a></li>
            <li><a href="#project">About</a></li>
            <li><a href="#project">Project</a></li>
            <li><a href="/contact">Contact</a></li>
        </ul>
    </div>
    <!--Buy me a coffee-->
    <div class="md:flex" id="list">
        <button class="bg-transparent border md:border-2 border-green-800 py-[7px] px-[10px] rounded-full text-white font-medium text-[12px] md:text-[15px]">
            Buy me a coffee
        </button>
    </div>
</header>

<style>
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans&family=Roboto&family=Rubik+Dirt&display=swap');
#logo{
    font-family: 'Rubik Dirt', cursive;
}
#list{
    font-family: 'Roboto', sans-serif;
}
#lsty>li>a:hover{
    background:transparent;
    height:100%;
    width:fit-content;
    border-bottom:2px solid #10b981;
    padding-bottom: 30px;
    transition: 0.5s ease-in-out;
}
</style>