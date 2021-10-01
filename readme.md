# ECE444-F2021-Lab3

Name: Pranav Agnihotri

This repo is a clone of https://github.com/nelaturuk/education_pathways

## Activity 1
![Activity 1 screenshot](https://user-images.githubusercontent.com/51279514/135678473-921a8cd6-baa9-4c67-ba6f-afb1742e858c.jpg)

## Activity 2
![Activity 2 screenshot](https://user-images.githubusercontent.com/51279514/135678645-0be601c6-2b2c-4fbe-91cc-94ed99b9f7bf.jpg)

## Activity 3
![Activity 3 screenshot](https://user-images.githubusercontent.com/51279514/135680260-f458809e-70e0-4b91-8ae7-6f5ac2dcfc1b.jpg)

## Activity 4
![Activity 4 screenshot 1](https://user-images.githubusercontent.com/51279514/135680275-bfb068e6-3c28-42ed-bc17-93a467241d54.jpg)

![Activity 4 screenshot 2](https://user-images.githubusercontent.com/51279514/135680292-654be570-6db2-4061-9b45-60a25f1a46d0.jpg)

## Activity 5
#### Non-Functional Requirement:
The **Usability** of the application is poor. Disregarding the primitive user interface, it is not clear how the search operation even works. The instructions on the application say to "restrict by one of Division OR Department OR Campus". Does that mean I can only filter on one? Can I not do multiple? What about the search term? Are the search terms a mandatory field?

The lack of clear instructions or helpful design to instruct which fields are mandatory or not leads to a very confusing user experience. It does not help that no matter what I choose, I am unable to get a search result to actually appear. So, is the application simply not functioning correctly, or am I inputting the search terms incorrectly? In the face of possible availability issues with the application, the user should have a clear understanding of when they might be using the application incorrectly, and when the application itself is having a problem. 

To improve the Usability of the application, the least I would do is have clearer language, pointing out which fields are optional and which aren't. I'd also probably give some examples via placeholder text in the search box. For example, should the "Search Terms" box be general words like "machine learning" or "philosophy"? Or are they expecting course codes? Placeholder texts in search boxes can make for a great way to give the user an idea of how to use the application properly for the best results. 
As well, when the search returns 0 results, there are no changes to the page to actually let me know the search was performed, and the number of results returned happened to be 0. I don't even know if my action went through. Thus, another thing to increase usability is to give the user concrete responses at every step so they know their actions are being processed. Something as simple as "We couldn't find any courses with those filters. Please try again" would be super helpful and go a long way.

#### Functional Requirement:
The application does not allow you to simply input your program or degree and return the courses for your program. That is often the place people start when building their schedules. They begin by picking from the core program courses, and then branch out to find electives. So, a functional requirement I would add is a filter on degree/minor/major/certificate/specialist.


