# My Reps

Enter your address to **find and contact your federal, state, county and local elected representatives Based on [my-reps-pbp](https://github.com/datamade/my-reps-pbp) by [DataMade](https://datamade.us/) and [Participatory Budgeting Project](http://participatorybudgeting.org/). Powered by the [Google Civic Information API](https://developers.google.com/civic-information/).

For more, read our launch blog post: [We find your reps so you don't have to](https://datamade.us/blog/we-find-your-reps-so-you-dont-have-to).

## Demo site: [myreps.datamade.us](http://myreps.datamade.us)

![My Reps](https://datamade.us/images/blog/2016-07-26-we-find-your-reps-so-you-dont-have-to/img1.jpg)

## Organizers: reuse our code!

We built this tool to be open source and easy to repurpose. Feel free to copy and reuse the My Reps codebase and customize the messaging and content for your issue.

If you need professional assistance, contact DataMade at info@datamade.us

## Reporting outdated or missing information

Information on elected officials comes from the [Google Civic Information API](https://developers.google.com/civic-information/), which aggregates data across the United States on elected officials in federal, state, county and local government offices. 

Sometimes data is outdated or missing. If you notice an issue with the data, please [report it to Google](https://docs.google.com/forms/d/e/1FAIpQLScA45a5Acnn6hK1R6dd45ttoVbI4tWc7oXl-pjQ-84yx7yuxA/viewform).


## Running locally

This website is built using Jekyll. You will need to [install it first](http://jekyllrb.com/docs/installation/).

``` bash
git clone git@github.com:datamade/my-reps.git
cd my-reps

# to run locally
jekyll serve -w
```

navigate to http://localhost:5000/

## Web dependencies

Data comes from the [Google Civic Information API](https://developers.google.com/civic-information/).

We used the following open source tools:

* [Bootstrap](http://getbootstrap.com/) - Responsive HTML, CSS and Javascript framework
* [jQuery Address](https://github.com/asual/jquery-address) - javascript library creating RESTful URLs
* [Google Civic Information API](https://developers.google.com/civic-information/) - API for looking up elected representatives in the USA

## Team

* Derek Eder - developer, content
* Eric van Zanten - developer

## Errors / Bugs

If something is not behaving intuitively, it is a bug, and should be reported.
Report it here: https://github.com/datamade/my-reps/issues

## Note on Patches/Pull Requests
 
* Fork the project.
* Make your feature addition or bug fix.
* Send a pull request. Bonus points for topic branches.

## Copyright

Copyright (c) 2016 DataMade. Released under the [MIT License](https://github.com/datamade/my-reps/blob/master/LICENSE).
