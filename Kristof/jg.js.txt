function osszeadas() {
    var aszam = document.getElementById("szamA").value;
    var bszam = document.getElementById("szamB").value;
    var eredmeny = parseFloat(aszam) + parseFloat(bszam);
    document.getElementById("eredmeny").innerHTML = eredmeny;
}

function kivonas() {
    var aszam = document.getElementById("szamA").value;
    var bszam = document.getElementById("szamB").value;
    var eredmeny = parseFloat(aszam) - parseFloat(bszam);
    document.getElementById("eredmeny").innerHTML = eredmeny;
}

function szoroz() {
    var aszam = document.getElementById("szamA").value;
    var bszam = document.getElementById("szamB").value;
    var eredmeny = parseFloat(aszam) * parseFloat(bszam);
    document.getElementById("eredmeny").innerHTML = eredmeny;
}

function osztas() {
    var aszam = document.getElementById("szamA").value;
    var bszam = document.getElementById("szamB").value;
    var eredmeny = parseFloat(aszam) / parseFloat(bszam);
    document.getElementById("eredmeny").innerHTML = eredmeny;
}
