---
title: "Ku Lab - Gallery"
layout: piclay
excerpt: "Ku Lab -- Gallery"
permalink: /pictures/equipment
---

# Lab equipment

### <a name="CellBiolLM"></a>[IPMB Cell Biology Core Lab: light microscopy](https://ipmb.sinica.edu.tw/en/core/Live-Cell-Imaging-Core-Lab)
<div id="homeid" class="col-sm-6">
<h5>Fluorescence Microscope (Zeiss Axio Imager Z1)</h5>
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/equipment/IMG_7876_Z1.jpeg" width="80%">
</figure>
</div>

<div id="newsid" class="col-sm-6" >
<h5>Polarized Light Microscope (LC-PolScope)</h5>
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/equipment/IMG_7877_PolScope.jpeg" width="80%">
</figure>
</div>





### <a name="2019YEP"></a>[IPMB Cell Biology Core Lab: flow cytometry](https://ipmbfcass.jimdo.com/)




<h5>20/Dec/2019</h5>
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_2019YEP %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/YearEndParties/2019_2020/reduced/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>




### Hotpot restaurant
<h5>1/Aug/2019</h5>
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/LabPhotos/P_20190801_195351.jpg" width="30%">
</figure>



### Lab warming party
<h5>3/May/2019</h5>

{% assign number_printed = 0 %}
{% for pic in site.data.pictures_LabWarming %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/LabWarming/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>




### Lab remodeling

#### After
Thanks to the support of IPMB and the help of many people, our lab remodeling was finished after four months of hard works.

{% assign number_printed = 0 %}
{% for pic in site.data.pictures_LabRemodelAfter %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/LabRemodelAfter/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>



#### During
<h5>Jan-Apr/2019</h5>


{% assign number_printed = 0 %}
{% for pic in site.data.pictures_LabRemodelDuring %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/LabRemodelDuring/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>



#### Before

{% assign number_printed = 0 %}
{% for pic in site.data.pictures_LabRemodelBefore %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/LabRemodelBefore/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>
