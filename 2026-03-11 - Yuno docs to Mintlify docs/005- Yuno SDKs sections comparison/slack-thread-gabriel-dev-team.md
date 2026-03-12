[yuno-docs-internal](https://writechoice.slack.com/archives/C06Q70SFVFB/p1773260972125179) Gabriel, Heitor, and you

Saved for later

Gabriel [Yesterday at 5:29 PM](https://writechoice.slack.com/archives/C06Q70SFVFB/p1773260972125179)  

[Mintlify migration]  [@Damián](https://writechoice.slack.com/team/U07FB71NRDL)fully migrated here:  [https://github.com/writechoiceorg/yuno-mintlify-migration](https://github.com/writechoiceorg/yuno-mintlify-migration)  

-   structure replicated from readme, with docs and api reference
-   you can get started with the changes, and adding content to the sdk section
-   all files are reorganized into folders
-   I need to organize the changelog section
-   Can you help me reviewing the links in homepage? It got scrambled with the links to files Caio had in his version. Its in this file:  `snippets/homepage/FeatureCards.jsx`

(edited)

Show 6 more replies

Damián [Yesterday at 5:34 PM](https://writechoice.slack.com/archives/C06Q70SFVFB/p1773261243987439?thread_ts=1773260972.125179&cid=C06Q70SFVFB)  

I have access now  ![:thankyou:](https://emoji.slack-edge.com/T02AQ4MK8KH/thankyou/5ea0724bdb079d4b.gif)

Damián [20 minutes ago](https://writechoice.slack.com/archives/C06Q70SFVFB/p1773316919144209?thread_ts=1773260972.125179&cid=C06Q70SFVFB)  

Hi  [@Heitor](https://writechoice.slack.com/team/U02QWCKQNEB), I'm currently working on the SDKs section within the new Mintlify migration repo. I've compared the two available versions:

-   **[SDKs](https://github.com/writechoiceorg/yuno-docs-fork/tree/yuno-docs-2026-03-11/SDKs)**: Created based on yesterday's discussion (focused on keeping only Full SDK and Secure Fields).
-   **[Yuno SDKs](https://github.com/writechoiceorg/yuno-docs-fork/tree/yuno-docs-2026-03-11/Yuno%20SDKs)****:**  The User Journey-oriented version we built a few weeks ago.

Check if you want. I think the  **[SDKs](https://github.com/writechoiceorg/yuno-docs-fork/tree/yuno-docs-2026-03-11/SDKs)**  version is better, so I will proceed with it. It aligns perfectly with the strategy of prioritizing  _Full Checkout_  and  _Secure Fields_  while providing a much cleaner structure for the new Mintlify site.Just two quick questions for final approval:  

1.  **React Native/Flutter**: Should I exclude these from the initial migration, or remove them? They are not included in the refactored version at this point.
2.  **Advanced Content**: Is it correct to keep customization options (e.g., custom card forms) within the  _Customization_  section?

If you agree with this, I will proceed to apply these changes directly to the migration repo Gabriel set up. (edited)

Heitor [1 minute ago](https://writechoice.slack.com/archives/C06Q70SFVFB/p1773318074745909?thread_ts=1773260972.125179&cid=C06Q70SFVFB)  

[@Damián](https://writechoice.slack.com/team/U07FB71NRDL):  

1.  if you and  [@Jonathan Castrillon](https://writechoice.slack.com/team/U08ES1EK6JE)  were already planning to remove those, I think it's ok.
2.  I think so.

I think the new organization is good. I just was wondering if we should keep the following content in the Overview section:  

-   References
-   Release Notes
-   Country Coverage
-   Language supported

Shouldn't we create another section to address this content below the guides?

Damián [Just now](https://writechoice.slack.com/archives/C06Q70SFVFB/p1773318160711739?thread_ts=1773260972.125179&cid=C06Q70SFVFB)  

I would like to have a section or a simple page for Release Notes. Let me work on it, and I'll get back to you with some improvements on that matter.