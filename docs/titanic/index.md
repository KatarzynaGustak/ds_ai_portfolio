# **_Eksploracyjna Analiza Danych - Titanic._**

*30.10.2024*

W projekcie przeprowadziłem analizę danych o pasażerach *RMS Titanic*, który zatonął 15 kwietnia 1912 roku. Zbiór danych zawiera szczegółowe informacje o pasażerach, takie jak klasa biletu, płeć, wiek, liczba rodzeństwa/małżonków na pokładzie, liczba rodziców/dzieci na pokładzie, cena biletu oraz port zaokrętowania.


Celem analizy było zrozumienie czynników, które mogły wpłynąć na przeżycie pasażerów.


*Podsumowanie:*
Na podstawie analizy danych o pasażerach Titanica można stwierdzić, że kobiety i pasażerowie pierwszej klasy mieli większe szanse na przeżycie katastrofy. Jednocześnie, zbyt mała liczba łodzi ratunkowych oraz ich nierównomierne rozmieszczenie przyczyniły się do tragicznych skutków katastrofy. Analiza danych ujawnia również nieścisłości i błędy w zapisie danych, które mogą wynikać z błędów w systemie rejestracji biletów.


<a href="titanic (2).ipynb" class="md-button md-button--primary">Pobierz Notebook</a>


<iframe
    id="content"
    src="titanic.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>