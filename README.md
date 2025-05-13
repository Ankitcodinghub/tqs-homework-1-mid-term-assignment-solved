# tqs-homework-1-mid-term-assignment-solved
**TO GET THIS SOLUTION VISIT:** [TQS Homework 1 Mid-term assignment Solved](https://www.ankitcodinghub.com/product/tqs-homework-1-mid-term-assignment-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93878&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;TQS Homework 1 Mid-term assignment Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

Develop a multi-layer web application, in Spring Boot, supplied with automated tests. This is an individual assignment.

Required elements Project scope

Your (web) application should provide details on COVID incidence data for a certain country/territory. You should consider at least the number of (new) cases for a day or period, but you may add more data (e.g.: data aggregation). Variations on the theme are acceptable and welcome, if related to public health surveillance.

The project must include different components (Figure 1):

<ol>
<li>A web app, minimalist, which allows users to enter or select a region/country and access its
Covid metrics, e.g.: last 3 days.
</li>
<li>Integration with external source(s). Actual data should be retrieved from a remote service. Your backend services will function as a client for a third-party API1, which you will access to obtain the required values.</li>
<li>Implement a cache2 to reduce the number of external accesses. Whenever a request is made to a remote API, you should cache the results; if the same (remote) data is requested (i.e., a duplicate request) then you should use the cached values. The cache should define a time-to-live policy and produce some basic statistics about its operation (count of requests, hits/misses). All data related to the cache operations is not required to be persisted [you may use a memory data structure, like a HashMap].</li>
<li>Provide your own REST API to expose COVID monitoring data to be invoked by external clients. Your API should allow to programmatically interrogate (your) backend for useful covid tracking data (e.g.: filtering by region, by days,…).
Your API should also provide an endpoint to get basic statistics on the use of the (internal) cache.
</li>
<li>Use a logging strategy to produce useful evidence of the actions/events that happened while using your software, for later inspection/debugging. Be sure to apply a standard logging library.</li>
</ol>
1 There are several API available (e.g.: https://rapidapi.com/collection/coronavirus-covid-19 ). Make your own survey and assessment, then choose one that you find easy to use to integrate in your project.

2 This should be a simple cache data structure, implemented by you; avoid the use of existing caching libraries (e.g.: JCache, Spring Boot Cache Manager).

</div>
</div>
<div class="layoutArea">
<div class="column">
TQS HW | 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Figure 1: Reference architecture: you need to implemente the blue elements; gray componentes represent integrations; pink elements are optional.

Technologies stack

The solution should be based on Spring Boot for the services/backend. You may implement the web (presentation) layer with any HTML/JavaScript framework or a templating system that integrates with Spring Boot (e.g.: thymeleaf).

Tests to implement

The project should include the automation of different types of tests:

<ol>
<li>A) &nbsp;Unit tests (suggestion: tests on the cache behavior; tests on “data validation”, “converters” or
“utils” in general, if applicable).
</li>
<li>B) &nbsp;Service level tests, with dependency isolation using mocks (suggestion: test your services in
isolation from external data provider).
</li>
<li>C) &nbsp;Integration tests on your API (suggestion Spring Boot MockMvc and/or REST-Assured).</li>
<li>D) &nbsp;Functional testing (on the web interface). Be sure to adopt a Behavior-driven approach (features with scenarios).</li>
</ol>
Quality metrics

The project should include code quality metrics (e.g., from Sonar Qube). To do this, you should also implement:

E) Integration of analysis with Sonar Qube (or Codacy). Note: If the Git project is public, it can be analyzed in SonarCloud.

Extra points (optional)

For extra points:

<ol start="6">
<li>F) &nbsp;The project works with more than one external source (remote API). It proactively switches between one or the other, either by configuration, or upon the (un)availability of the sources.</li>
<li>G) &nbsp;The project uses a Continuous Integration framework, with the automation of testing and static code analysis (e.g.: GitHub Actions, GitLab CI/CD)</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
