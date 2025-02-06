# **_Exploratory Data Analysis - Daily Lifestyle and Academic Performance of Students._**

*30.11.2024*

This project focused on the exploratory data analysis of the *"Daily Lifestyle and Academic Performance of Students"* dataset, downloaded from Kaggle. The dataset contains information about the lifestyle and academic performance of 2,000 students from India during the 2023/2024 academic year. The data was collected via a Google Form survey and includes variables such as study hours, sleep, physical activity, time spent on socializing and extracurricular activities, stress levels, and GPA. 

The goal of this project was to analyze the relationships between daily habits, academic performance, and student well-being. 


*Key Findings:*
Relationship between Study Hours and Academic Performance:
There is a clear correlation between study hours and GPA. High GPAs (above 3.9) are observed among students studying more than 8 hours per day.

Impact of Stress:
Students with high stress levels tend to achieve better academic results, but this comes at the expense of reduced sleep, physical activity, and social interactions.

Sleep and Academic Performance:
In the high-stress group, sleep duration did not significantly affect GPA. High academic performance was observed among students sleeping both 5 and 9 hours.

Physical and Social Activities:
Increased physical activity correlates with a decrease in socializing time. In the high-stress group, more time spent on physical and social activities is associated with lower GPAs.


*Summary:*
The analysis demonstrates that high academic performance is primarily achieved by students dedicating significant time to studying, often at the cost of their health and overall well-being. This raises the question of whether sacrificing physical activity, social interactions, and adequate sleep is worth achieving higher academic results. During this project, I utilized additional Python libraries for data visualization, such as Matplotlib, Plotly and Seaborn, which helped uncover and illustrate complex patterns within the dataset.


<a href="Student_lifestyles.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>


<iframe
    id="content"
    src="Student_lifestyle.html"
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