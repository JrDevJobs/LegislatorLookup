# <a href='http://www.jrdevjobs.com' target='_blank'>Jr.DevJobs</a> Challenge: Legislator Lookup

## Introduction
In this challenge you will create a webpage using the <a href='https://sunlightlabs.github.io/congress/' target='_blank'>Sunlight Foundation's Congress API</a> to lookup United States legislators by zip code. For each legislator you will display the details defined in the [user story](#userstory).

You are free to do this in any language or framework, however the sample is written in JavaScript.

## Getting Started
To begin, Fork this repository to your GitHub account by clicking the Fork icon in the upper-right section of this page.

![Forking Image](https://s3-us-west-2.amazonaws.com/jrdevsimages/repos/fork_button.jpg)

*If you're new to Forking, we suggest reading the <a href='https://help.github.com/articles/fork-a-repo' target='_blank'>GitHub documentation</a> before moving forward.*

Finally, in order to use the Congress API you must register for a <a href='http://sunlightfoundation.com/api/accounts/register/' target='_blank'>free API Key</a> from the Sunlight Foundation.

## <a name='userstory'></a>User Story
As a user, I want to view the details of the legislators in my area by providing my zip code.

#### Basic Details

* First and last name
* Chamber of congress and party affiliation
* Link to their government bio page (ex. <a href='http://woodall.house.gov/' target='_blank'>http://woodall.house.gov/</a>)
* Phone number and email address

#### Advanced Details

* Profile picture *(Hint: This <a href='https://github.com/unitedstates/images' target='_blank'>Congressional Images Repo</a> hosts images listed by each legislator's `bioguide_id`)*
* Links to sponsored bills (including the bill ID and title if available) *(Hint: Pass a legislator's `bioguide_id` to the `/bills?apikey=API_KEY&sponsor_id__in=` end-point)*
* Icons/Links to social media networks

## Example
The screenshot below is an example of how to display the details of legislators in the 30024 zip code.

![Legislator Details](https://s3-us-west-2.amazonaws.com/jrdevsimages/repos/legislator_1.png)
