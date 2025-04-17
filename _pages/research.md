---
layout: archive
title: "Working Papers"
permalink: /research/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}


* "The Privacy-preserving Data-driven Inventory Management." with Karan Girotra and Elena Belavina. [[Document](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5219878)]
   * <details>
     <summary>Abstract</summary>
     
     The use of customer data (demographics, past purchases, etc.) for inventory management can improve firm profits and customer service levels. Yet, large-scale use of such data in production environments increases the risks of breaching customers' privacy. In this study, we develop differential-privacy based privacy-preserving adaptations for two data-driven newsvendor paradigms: the usual two-step estimate-then-optimize method, and the newer one-step joint estimate-optimize method. We characterize the tradeoff between privacy loss and profits and show that the privacy-preserving one-step joint approach outperforms the privacy-preserving two-step approach. In essence obfuscating customer data is less costly in terms of profits, when we account for how estimations will be used in downstream optimization problems, we can privatize outputs with less noise and more targeted noise injection. We subsequently construct a generic model to explore the broader impact of implementing these privacy-preserving algorithms on both the firm and customers. Our analysis uncovers a win-win scenario for both the firm and customers under the two-step and one-step privacy-preserving paradigms respectively, as long as customers demonstrate any degree of privacy concerns. The feasibility of such an outcome depends on both the choice of paradigm and critical ratio. Calibration based on a real-world dataset reveals that the one-step algorithms showcase a 3 to 4 times stronger privacy protection and up to 30% increase in achieved profit than the two-step counterpart. Even with lower customer privacy sensitivity, the one-step algorithms can boost profits by 12% while maintaining robust privacy protection—an achievement unattainable with the two-step algorithm.
  
     </details>

* "Strategic Private Information Acquisition for News Vendor." with Karan Girotra and Elena Belavina. *Work in progress*.

* "Generative AI Copilot in a Production Network." with Karan Girotra and Elena Belavina. *Work in progress*.
