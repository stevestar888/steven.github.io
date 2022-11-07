---
layout: post
title: I Made an Improved Excel Budget Spreadsheet
subtitle: It also estimates taxes & can deal with income/expenses on a fortnightly, monthly, quarterly, or annual basis
cover-img:
thumbnail-img:
share-img: 
tags: [side-project, personal-finance]
---

Download: [“Comprehensive Budget” (.xlxs)](../blog-assets/2022-11-04/Comprehensive%20Budget.xlsx)

# Background
A couple of Bowdoin friends who just started working full-time this summer asked me to send them a copy of the budget I was using. However, what I was using was ripped off from my parents—and it was more functional than aesthetic. Now that I've been managing my real-world finances for more than a year, and now that I learned how to use excel for real, I thought I could make something better (for both myself and my friends to use). I’m calling this improved budget the “Comprehensive Budget.” 

I wanted a budget that had more features, but was still very intuitive to use. I was trying to strike a balance between functionality and simplicity because my philosophy around making a budget is it gives you an idea of how much you can sustainably spend. Some weeks you may be over budget, some weeks you may be under budget—and both are OK. You'll be fine as long as you're not wildly off, which is why getting a sense of rough numbers by writing down income and expenses on a budget is so useful.

I started by combing through spreadsheets online to get ideas about what I wanted (and didn’t want) to include. Funny enough, I used the "Google Power Search" tool to refine my search to only excel files (read me about that in [this post](https://stevestar888.github.io/2021-02-02-past-two-hackathons/#:~:text=Google%20Power%20Search%20(June%202020%20during%20Hack%20the%20Northeast))). The one I liked the most was (not even kidding) found on https://moneysmart.gov.au/budgeting/budget-planner, which looks like it was created by the Australian government of all people! 

### I’ll talk about two cool things about this budget 🤓
1. The spreadsheet is “frequency agnostic”, so you can enter a piece of income or an expense and then specify if it happens biweekly, monthly, quarterly, or yearly. Separately, you can toggle to see the budget in a biweekly, monthly, quarterly, or yearly view. For example, you can enter your annual salary and monthly rent, and see how your budget would look on a biweekly, monthly, quarterly, or yearly view. The only place I saw this feature was from the budget on that Australian government website, and I really like this feature. So I shamelessly stole it...

2. I built the calculation for federal income tax straight into the spreadsheet in a separate tab called “Tax Calculation.” This tab pulls copies over relevant numbers from the Budget tab (like your salary, bonus, Traditional 401k and IRA contributions, HSA contributions, etc). If those numbers are what you want to use as inputs, then you can reference them directly. If not, or you want to use a modified number, you can always enter your own. I tried to build in a lot of flexibility so the numbers can be adjusted as you go. Another cool thing is the spreadsheet breaks down how much tax you pay in each tax bracket. 

### A couple of additional things you should know about the “Comprehensive Budget”:
1. On the budget tab, the only cells you'll need to change are in columns D and F. If the income/expense should be a % of something (e.g., your bonus is a % of annual salary), then you can put the % in column C and replace column D with an appropriate formula.

2. You can toggle the frequency with cell H2! Please use this because it’s very cool and very borrowed!

3. Inserting / deleting rows *shouldn’t* be a problem. But, just to be safe, it's probably better to just rename unused categories before inserting / deleting rows. If you must insert a new row, then make sure the sectional total adds up correctly still (alternatively, insert a row in the middle of a section).

4. Some sections and rows probably won’t be applicable. Instead of outright deleting them, it may be easier to just hide it: click the row #, right click, click hide. 

5. I think this is clear, but the notes regarding contribution limits of tax-advantaged accounts, tax bracket #s, standard deduction #, etc. are all for 2023. Modify accordingly if this gets out of date 😬. 

6. At the bottom of the budget, the pie chart showing how your expenses break down is accurate (or at least should be). The legend will show just a color without a label if a certain section totals up to $0. You can just ignore that. 

# Wrapping up
While building this, I gained a more thorough understanding of the tax brackets. If you hear somebody say, “if I make $x more this year, that’ll put me in a higher tax bracket and my tax rate goes up”, that’s misleading. Even if the extra $x of income bumps you into a higher tax bracket, it’s only the portion that made it into the higher tax bracket that will be taxed at a higher rate. Speaking from a taxation standpoint, making more money is strictly beneficial. 

While building this, I was also reminded of how awesome excel is. Reminds me of this meme: 

(The entire financial system is held up by excel)[../blog-assets/2022-11-04/excel_meme.png]

I haven't used excel in any real capacity since leaving my Associate Equity Analyst role at Morningstar in September, so this was a throwback to those times. Luckily, the important keyboard shortcuts are still with me, so that's good. May be I'm just cheery because this spreadsheet is super lightweight and excel couldn't find a reason to crash. Ha!

Download: [“Comprehensive Budget” (.xlxs)](../blog-assets/2022-11-04/Comprehensive%20Budget.xlsx)