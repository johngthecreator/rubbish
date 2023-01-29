<script>

</script>

<nav>
    <a id="homeLink" href="/"><h1>depo</h1></a>
    <details role="list" dir="rtl">
        <summary id="nav" aria-haspopup="listbox">MENU</summary>
        <ul role="listbox">
          <li><a href="/upload">UPLOAD</a></li>
          <li><a href="/locker">LOCKER</a></li>
          <li><a>ALTERN</a></li>
        </ul>
    </details>
</nav>

<style>
    h1 {
        color: white;
    }

    a {
        font-weight: 700;
    }

    nav {
        padding: 15px;
    }

    a#homeLink {
        text-decoration: none;
        color: white;
    }


    summary#nav {
        font-size: 20px; 
        font-weight: 700; 
        background-color: #303030;
        color: white;
        display: flex;
        align-items: center;
        border: 2px solid white;
        border-radius: 5px;
        padding: 5px 15px;
    }
    summary#nav::after{
    content: none;
    }
    summary {
        height: 10px;
    }
    details[role=list] {
    box-shadow: 0 !important;
    outline: none !important;
    }

</style>