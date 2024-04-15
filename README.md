# nodejspatikaOdev1
Dairenin Alanı
const arguments = process.argv.slice(2);
function alanHesapla(r) {
    console.log(`Yarıçapı ${r} olan dairenin alanı ${r * r * 3.14}`);
}
alanHesapla(arguments[0]);
