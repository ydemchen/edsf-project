---
title: Home EDSF
layout: blank
---
{% include page_head.html %}

{% include nav.html %}

<div class="container">
	<div class="row">
		<div class="col-xs-12">
			<div class="claim">
				<img alt="EDISON" src="/assets/images/EDISON-LOGO.png" >
				<h1>Building the Data Science Profession </h1>
			</div>
		</div>
	</div>
</div>

<div class="container">
	<div class="row">
		<div class="col-xs-12">
			<h1>What Have EDISON Project delivered</h1>
		</div>
	</div>
	<div class="row">
		<div class="col-md-4">
			<h2><span class="fa-stack"><i class="fa fa-circle fa-stack-2x"></i><i class="fa fa-terminal fa-stack-1x fa-inverse"></i></span>EDISON Data Science Framework</h2>
			<p class="lead">Manage multi-cloud application deployment, software-defined networks, and federated identities.</p>
			<p><a class="btn btn-primary btn-lg btn-block" href="/software.html"><i class="fa fa-book fa-inverse"></i>&nbsp;<b>Learn</b> about our tools</a></p>
			<p><a class="btn btn-primary btn-lg btn-block" href="/tryit.html"><i class="fa fa-cloud-upload fa-inverse"></i>&nbsp;<b>Try</b> our software</a></p>
		</div>
		
</div>

<div class="container challenges">
	<div class="row">
		<div class="col-xs-12">
			<h1>What does EDSF solve?</h1>
		</div>
	</div>
	<div class="row">
		<div class="col-md-6">
			<a href="about.html#deployment"><h3><span class="fa-stack"><i class="fa fa-circle fa-stack-2x"></i><i class="fa fa-cloud-upload fa-stack-1x fa-inverse"></i></span><span>Multi-cloud deployment and scaling of federated applications</span></h3></a>
		</div>
		<div class="col-md-6">
			<a href="about.html#federatedidentity"><h3><span class="fa-stack"><i class="fa fa-circle fa-stack-2x"></i><i class="fa fa-unlock fa-stack-1x fa-inverse"></i></span><span>Using federated identities for secure access control</span></h3></a>
		</div>
	</div>
	<div class="row">
		<div class="col-md-6">
			<a href="about.html#network"><h3><span class="fa-stack"><i class="fa fa-circle fa-stack-2x"></i><i class="fa fa-sitemap fa-stack-1x fa-inverse"></i></span><span>Automating network service deployment for enhancing application security</span></h3></a>
		</div>
		<div class="col-md-6">
			<a href="about.html#brokering"><h3><span class="fa-stack"><i class="fa fa-circle fa-stack-2x"></i><i class="fa fa-exchange fa-stack-1x fa-inverse"></i></span><span>Cloud service brokering and matchmaking</span></h3></a>
		</div>
	</div>
	<div class="row">
		<div class="col-md-6">
			<a href="about.html#monitoring"><h3><span class="fa-stack"><i class="fa fa-circle fa-stack-2x"></i><i class="fa fa-tachometer fa-stack-1x fa-inverse"></i></span><span>Distributed monitoring and logging</span></h3></a>
		</div>
		<div class="col-md-6">
			<a href="about.html#security"><h3><span class="fa-stack"><i class="fa fa-circle fa-stack-2x"></i><i class="fa fa-power-off fa-stack-1x fa-inverse"></i></span><span>Cloud Security Bootstrapping</span></h3></a>
		</div>
	</div>
</div>

<div class="container">
	<div class="row">
		<div class="col-xs-12">
			<h1>Follow us:
				{% for icon in site.data.social-icons %}
				<a class="social-icon-link {{ icon.class }}" href="{{ icon.url }}">
					<img src= "{{ icon.class | prepend: '/assets/images/' | append: '.svg' }}" alt='cyclone-project@{{ icon.class }}' width="42">
				</a>
				{% endfor %}
			</h1>
		</div>
	</div>
</div>

{% include page_footer.html %}
