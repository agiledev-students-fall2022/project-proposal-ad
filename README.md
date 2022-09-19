
# Recipe Grandma :older_woman: (Proposal 1)

## Contributors

Geon Tack Lee, Yeonie Heo, Jennifer Zheng, Oyungerel Amarsanaa
## What?

It is an automated recipe suggester based on the ingredients you have at home. This software will recognize your food ingredients through a quick snapshot and recommend the food you can cook with what you have.
## Why?

This is convenient for people who struggle to decide or do not know what to cook for their meals.

## For whom?

* Highschool or college students who are living on their own
* Busy workers
* Confused/distressed parents

## How?

1. Users will grab their phones and take a photo of their incredients spread out on a table or in their fridge.
2. The app will scan the incredients.
3. The app will automatically match the ingredients with top-rated recipes from the database.

## Scope

* This app needs to have a handful of recipes with ingredients to sucessfully suggest a meal to the users. Creating a solid database will be challenging as the recipes must cover a variety of cusines.
* Implementing precise image recongnition of the ingredients may be demaning (requires Computer Vision knowledge).
* Implementing a search algorithm that links users' ingredients with potential recipes may be time confusing.

---

# noFlakes :no_entry_sign: (Proposal 2)

## Contributors

Nghia Nim
## What?

A credit tracking app to keep you and your friends from flaking on appointments!

## Why?

So often do people (not excluding myself) flake on plans with their friends, family, or even work! Do you ever have that one plan that you and your friends were surely committed to but in the end cannot attend because of a sudden "other commitment"? Looks like your plan wasn't a real commitment afterall. :broken_heart: 

## For whom?

* Anyone who wants to plan something with someone and wants to keep themselves accountable.
* Event organizers who want to keep their attendance high can invite only people with some minimum amount of credit.
* People who attend meetings often can prioritize those who have higher credit.
* Anyone who wants to start building healthy commitment habits.

## How?

* An app that tracks and lets you look up the credibility (flakiness) of someone.
* Point system: Everyone who signs up with an email will get a default number of credit (say 300). 
* Users of the app can schedule an event with each other, and in groups, but has to be in advance of at least 24 hours, and can only schedule at most twice per day. 
* Points will be awarded to those who show up for the event, and vice versa, deducted for those who doesn't or cancel last minute.
* Show-ups can confirm their arrival using GPS.
* The amount of points awarded will depend on the number of people attending, punctuality, your current credit, etc. The function to calculate the point will be logarithmic and capped at some amount (TBD), so higher credit will be harder to achieve. Can look at credit functions used by banks for reference.
* Flaking will incur heavy penalties.

## Scope

* Needs a minimalistic UI like most banking apps.
* The credit system needs to be well-designed and not abusable, which will require a lot of user testing.
* Location data can be provided using APIs.
* All the functionalities and UI should be implementable in a span of 3 months!

## Add-ons

* Use machine learning to filter fake accounts (e.g., bot emails and emails that were newly created). There will be an approval process like when you apply for a credit card.