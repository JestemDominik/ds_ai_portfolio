# Analiza danych i budowa modelu predykcyjnego dla sklepu internetowego

W ramach kursu MIT:Data Science and Machine Learning zrealizowałem projekt, którego celem była analiza danych klientów sklepu internetowego oraz zbudowanie modelu klasyfikacyjnego przewidującego konwersję. Projekt od podstaw objął eksploracyjną analizę danych (EDA), przetwarzanie danych oraz budowę i ocenę modelu Decision Tree Classifier.

Dodatkowo przygotowałem własne rekomendacje biznesowe na podstawie wyników analizy, wskazujące, które cechy użytkowników i zachowania mają największy wpływ na prawdopodobieństwo zakupu. Był to pierwszy projekt który nauczył mnie pełnego procesu analizy danych i wdrażania modeli predykcyjnych.

<a href="E-commerce_Decision_Tree.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="E-commerce_Decision_Tree.html"
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
