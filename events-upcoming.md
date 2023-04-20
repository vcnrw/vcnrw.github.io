---
layout: default
title: Kommende Events
---

<!-- Posts Index
================================================== -->
{% if paginator.previous_page %}
{% if paginator.previous_page > 0 %}
<div id="jumptopageof"></div>
{% endif %}
{% endif %}    

<section class="recent-posts row">

    <div class="col-sm-8">
        <div class="masonrygrid row listrecent">

            {% for post in paginator.posts %}
         
            {% include postbox.html %}

            {% endfor %}

        </div> 

        <!-- Pagination -->
        <div class="bottompagination">

            <span class="navigation" role="navigation">

                {% include pagination.html %}

            </span>

        </div>

    </div>

    <div class="col-sm-4">
            {% include sidebar.html %}
    </div>

</section>