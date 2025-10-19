---
layout: archive
title: "Working Papers"
permalink: /research/
author_profile: true
---

{% include base_path %}

<style>
  /* Page-level settings */
  .research-page{
    line-height: 2;          /* 2× spacing */
    max-width: 1000px;       /* keep content to 1000px */
    margin: 0;               /* keep content flush-left (not centered) */
    padding-right: 2rem;     /* tiny breathing room on very small screens */
  }

  /* Abstract body gets 1.5; summary keeps the page default (2) */
  .research-page details.abstract { line-height: 1.5; }
  .research-page details.abstract > summary { line-height: 2; }
</style>

<div class="research-page">
  <ul class="sublist">
    <li>
      "Privacy-preserving Data-driven Inventory Management." with Elena Belavina. <em>Major Revision at <i>Management Science</i></em>. <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5219878" target="_blank">[SSRN]</a>
      <ul class="sublist">
        <li>
          Job Market Paper
        </li>
        <li>
          Third Place in YinzOR Conference Flash Talk Competition
        </li>
        <li>
          Accepted to NYC Privacy Day at Google
        </li>
        <li>
          <details class="abstract">
            <summary>
              Abstract
            </summary>
            The use of customer data (demographics, past purchases, etc.) for inventory management can improve firm profits and customer service levels. Yet, large-scale use of such data in production environments increases the risks of breaching customers' privacy. In this study, we develop differential-privacy based privacy-preserving adaptations for two data-driven newsvendor paradigms: the usual two-step estimate-then-optimize method, and the newer one-step joint estimate-optimize method. We characterize the tradeoff between privacy loss and profits and show that the privacy-preserving one-step joint approach outperforms the privacy-preserving two-step approach. In essence obfuscating customer data is less costly in terms of profits, when we account for how estimations will be used in downstream optimization problems, we can privatize outputs with less noise and more targeted noise injection. We subsequently construct a generic model to explore the broader impact of implementing these privacy-preserving algorithms on both the firm and customers. Our analysis uncovers a win-win scenario for both the firm and customers under the two-step and one-step privacy-preserving paradigms respectively, as long as customers demonstrate any degree of privacy concerns. The feasibility of such an outcome depends on both the choice of paradigm and critical ratio. Calibration based on a real-world dataset reveals that the one-step algorithms showcase a 3 to 4 times stronger privacy protection and up to 30% increase in achieved profit than the two-step counterpart. Even with lower customer privacy sensitivity, the one-step algorithms can boost profits by 12% while maintaining robust privacy protection—an achievement unattainable with the two-step algorithm.
          </details>
        </li>
        <li>
          <details class="abstract">
            <summary>
              10-minute flash talk
            </summary>
            <iframe
              width="528"
              height="297"
              src="https://www.youtube-nocookie.com/embed/JJjOuLfzm5s"
              title="YouTube video"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
              allowfullscreen
              loading="lazy">
            </iframe>
          </details>
        </li>
      </ul>
    </li>
    <li>
      “Mechanism Design for Generative AI Copilot in a Sequential Production Process.” with Karan Girotra and Elena Belavina. <i>Working Paper (draft upon request)</i>.
    </li>
    <li>
      "Data-driven Decisions in Supply Chains: Contracts, Algorithms, and Efficiency." with Xiaoyue Yan, Karan Girotra and Elena Belavina. <i>Working Paper (draft upon request)</i>.
    </li>
    <li>
      "Privacy-preserving Collaborative Learning." with Karan Girotra and Elena Belavina. <i>Work In Progress</i>.
    </li>
  </ul>

</div>