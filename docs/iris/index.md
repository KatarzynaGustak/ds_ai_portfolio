# **_Eksploracyjna Analiza Danych - Irysy._**

 *24.10.2024*

Projekt ten to eksploracyjna analiza danych na zbiorze danych o Irysach. Jest to klasyczny i nieskomplikowany zbiór, często używany w początkowych etapach nauki. Zawiera pomiary długości działek kielicha, szerokości działek kielicha, długości płatków i szerokości płatków dla trzech różnych gatunków kwiatów Iris: *Iris-setosa, Iris-versicolor i Iris-virginica.*


Był to jeden z moich pierwszych, samodzielnych projektów.


Sprawdź, który z analizowanych gatunków Irysów jest największy !!


<a href="EDA_irysy (6).ipynb" class="md-button md-button--primary">Pobierz Notebook</a>


<iframe
    id="content"
    src="irisy.html"
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