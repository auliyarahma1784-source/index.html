        <b>Matematika SD</b><br>
        Penulis: Budi<br>
        Status: <span class="status-no">Dipinjam</span>
    </div>
</div>

<script>
function login(){
    let nama=document.getElementById("nama").value;
    if(nama===""){ alert("Isi nama dulu ya"); return;}
    document.getElementById("loginPage").classList.add("hidden");
    document.getElementById("homePage").classList.remove("hidden");
    document.getElementById("halo").innerText="Halo, "+nama+" 👋";
}

function showCari(){
    document.getElementById("homePage").classList.add("hidden");
    document.getElementById("cariPage").classList.remove("hidden");
}

function back(){
    document.getElementById("cariPage").classList.add("hidden");
    document.getElementById("homePage").classList.remove("hidden");
}
</script>

</body>
</html>
