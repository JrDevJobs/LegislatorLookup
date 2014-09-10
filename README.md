# [Jr.DevJobs](http://www.jrdevjobs.com) Challenge: Legislator Lookup

## Introduction
In this challenge you will use the [Sunlight Foundation's Congress API](https://sunlightlabs.github.io/congress/) to lookup United States legislators by zip code. For each legislator you will display the details defined in the [user story](#markdown-header-user-story).

You are free to do this in any language or framework, however the sample is written in JavaScript.

## Getting Started
To begin, Fork this repository to your GitHub account by clicking the Fork icon in the upper-right section of this page.

![Forking Image](https://s3-us-west-2.amazonaws.com/jrdevsimages/repos/fork_button.jpg)

*If you're new to Forking, we suggest reading the [GitHub documentation](https://help.github.com/articles/fork-a-repo) before moving forward.*

Finally, in order to use the Congress API you must register for a [free API Key](http://sunlightfoundation.com/api/accounts/register/) from the Sunlight Foundation.

## User Story
As a user, I want to view the details of the legislators in my area by providing my zip code.

#### Basic Details

* First and last name
* Chamber of congress and party affiliation
* Link to their government bio page (ex. [http://woodall.house.gov/](http://woodall.house.gov/))
* Phone number and email address

#### Advanced Details

* Profile picture *(Hint: This [Congressional Images Repo](https://github.com/unitedstates/images) hosts images listed by each legislator's `bioguide_id`)*
* Links to sponsored bills (including the bill ID and title if available) *(Hint: Pass a legislator's `bioguide_id` to the `/bills?apikey=API_KEY&sponsor_id__in=` end-point)*
* Icons/Links to social media networks

## Example
The following screenshot shows a snippet of displaying the details of legislators in the 30024 zip code.

![Legislator Details](https://s3-us-west-2.amazonaws.com/jrdevsimages/repos/legislator_1.png)
