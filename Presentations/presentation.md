---
title: |
  | What should we do and why?
  | Work principles for behavioral insights teams.
author: Jake Bowers
institute: | 
     | Political Science and Statistics, University of Illinois @ Urbana-Champaign
     | Fellow, White House Social and Behavioral Sciences Team
date: 'May 22, 2016'
output:
  beamer_presentation:
    keep_tex: yes
    latex_engine: xelatex
    slide_level: 2
    template: sbst.beamer
    toc: yes
  ioslides_presentation:
    css: sbstpresentation.css
    logo: ../graphics/SBSTLightBulb.png
    smaller: yes
---




# Introducing Behavioral Insights Teams

## Behavioral Insights Teams in Government



> A growing body of evidence demonstrates that behavioral science insights---research findings from fields such as behavioral economics and psychology about how people make decisions and act on them---can be used to design government policies to better serve the American people. (President Barak Obama's Executive Order 13707 "Using Behavioral Insights To Better Serve the American People")

[The UK Nudge Unit](http://www.behaviouralinsights.co.uk/about-us/)

\medskip

[The White House SBST](http://sbst.gov)

\medskip

[The EU](https://ec.europa.eu/jrc/en/event/conference/biap-2016#country-overviews)

\medskip

[New South Wales Intro to Behavioral Insights Teams](https://www.youtube.com/watch?v=pDub6gG1yxw&feature=youtu.be)

\medskip

\only{<2>}{
\textbf{\textcolor{blue}{
BI teams translate (and extend) knowledge from (mostly) randomized experiment-based research into public policy.}
}}

## Design for person oriented government

UX (user experience) designers interview and observe users of products throughout the cycle of iterative production.

\medskip

> Cognitive empathy requires not a face, not preferences and demographics, but the underlying reasoning, reactions, and guiding principles. Without these you cannot develop empathy. And if you cannot develop empathy, you cannot wield it---you cannot walk in someone’s shoes. [Describing Personas by Indi Young](https://medium.com/@indiyoung/describing-personas-af992e3fc527#.vpydktp99)

> At the beginning of a user experience research project, it’s okay to talk about what the segments look like. The segments are one view of a user profile; personas are another. But they’re based on totally different data. Segments come from self-reported survey data, usually. Personas should be developed after observing users in their own contexts doing their own tasks. [Avoiding Demographics When Recruiting Participants: An Interview with Dana Chisnell](https://articles.uie.com/recruiting_participants/)

## Example: myUSA

[MyUSA](https://github.com/18F/myusa-ux/blob/master/images/front%20page.png)

[UX Transcript](https://github.com/18F/myusa-ux/blob/master/research/usability/sprint22_research-data.md)

[UX report on MyUSA](https://github.com/18F/myusa-ux/blob/master/research/usability/sprint33_small-business-results.md)


## Science for person oriented government

\includegraphics[width=.9\textwidth]{ScienceInTheHouse.png}

## What follows from valuing science? 

Why not Behavioral Claims Teams?  Why does science produce "insights"? 

\medskip


1) No one study produces certain knowledge (there is no certain knowledge). 
2) No one person produces certain knowledge. Investigators must be comfortable with uncertainty and doubt.
3) Other aspects of research design (for example, randomization, pre-registration, other aspects of learning-enhancing or credibility-enhancing transparency)



\bigskip
\only{<2->}{

BTW, these ideas enable frequentist statistical inference: a $p$-value / confidence interval is a $p$-value/confidence interval, no more no less.
}

## What follows from a person oriented approach to public policy?

If we believe better guidance for public policy arises from behavioral science insights and methods combined with qualitative research from user experience teams, then how should behavioral insights team members act?

I suggest: with humility and valuing community.

# Concrete Actions for 2016

## Action 1: Use plain text

Writing memos, reports, or analyses in formats that are propriety and/or likely to change quickly and/or cost money to read raises barriers to collaboration across both space (with others) and time (with the team itself should it desire to use materials from past studies for the future.)^[This poses a challenge for groups where the government dictates the tools.] This essay, for example, is written in [markdown](https://daringfireball.net/projects/markdown/).^[Specifically, it uses [pandoc](http://pandoc.org/) flavored markdown.]

## Action 2: Use open-source and multi-platform tools

Plain text code written for interpretation by an expensive and single platform computing language may be readable in the future, but will be of little use to those who desire to help or learn from the team. This suggests that teams only use tools like R or python or other open-source analysis and/or markup languages that are available on free operating systems and across platforms.

## Action 2a: Assume others will want to reproduce the work.

The fact that one has written open source code written in plain text does not mean that others can effectively learn from or copy and improve on one's work. This means that all analyses should be written as if someone else, who is not a part of the team's social network, ought to be able to reproduce the analyses of the team (to the extent possible given data sharing limitations). Tools here include [Rmarkdown](http://rmarkdown.rstudio.com/) and processes for tracking dependencies among files like the [make](http://robjhyndman.com/hyndsight/makefiles/) system and [R packages](http://r-pkgs.had.co.nz/).^[Insert versions for python.]

## Action 3: Work in the Open Take advantage of the cloud

My favorite way to work in the open right now is to use [GitHub](http://github.com) because it not only encourages a workflow in which people copy and improve and change others' code, but prevents old files from being clobbered with new files, tracks and threads discussions about topics, and enables online editing and easy website creation for quick sharing of documents and results.


## Action 4: Plan for Heterogeneous Treatment Effects



# End Matter

## Sources and Inspirations

This document builds on the [*commitment of the federal government to
openness*](https://www.whitehouse.gov/open) and especially on my 
interpretation of the detailed [*US Open Government National Action Plan
3.0*](https://www.whitehouse.gov/sites/default/files/microsites/ostp/final_us_open_government_national_action_plan_3_0.pdf)

\bigskip

The injunction to "work in the open" (and internally to "share not send") comes from [*18F*](https://18f.gsa.gov/2014/07/31/working-in-public-from-day-1/)


\bigskip

This document is currently hosted on github at <http://github/sbstusa/transparency>. Comments welcome. 

\appendix

## More inspiration from 18F

[18F Design Principles](https://github.com/18F/myusa-ux/blob/master/research/memos/design-principles.md)

[18F Design Principles Definition](https://pages.18f.gov/design-principles-guide/define/)

[18F Design and Production Process](https://pages.18f.gov/lean-product-design/)


## More Inspiration: Statements of Principles

[EGAP Design Principles](http://egap.org/egap-statement-of-principles) 

[Australia Government Design Principles](http://www.designprinciplesftw.com/collections/australia-designgov-principles)

[Code for America Design Principles](http://www.designprinciplesftw.com/collections/principles-for-21st-century-government)
