---                                                                             
layout: media                                                                   
title: "AnomaLease"
categories: projects
excerpt: "An NLP approach to quickly group common commercial lease clauses for closer inspection"
ads: false                                                                       
modified: " "
share: false
image:
  teaser: cluster-securitydeposit.png
  credit: Jason P Chang
---                                                                             

<img src="{{ site.url }}/images/{{page.image.teaser}}" /> 
<div><em>Projection of tf-idf vectors in two dimensions after Latent Semantic Analysis. Red points correspond to a group of insurance clauses and blue points correspond to all other clauses.</em></div>
<p>
Commercial lease agreements are not only long, but often tedious and boring to read. The nature of a commercial lease agreement makes it the perfect document for landlords to hide unfavorable terms from potential tenants. Using natural language processing techniques and clustering, I successfully group similar clauses across different lease agreements. From the security deposit clause group, I build distributions of useful negotiation terms, including the ratio of security deposit to monthly rent and the number of days before a landlord must return the security deposit to the tenant. These results provide invaluable context to any commercial lease agreement in California.
</p>

<img src="{{ site.url }}/images/days.png" /> 
<div><em>Distribution of the number of days before a landlord must return the security deposit to the tenant.</em></div>

<b>Links</b><br />
<a href="https://medium.com/@chang.jasonp.insight/anomalease-fc24b4bd166d" target="_blank">Medium post</a>
