# Javascript & MongoDB Catchup Module

This week, based on the learning needs you identified, we will focus on
Javascript and MongoDB.

There are a number of exercises and guidance materials below. They are drawn
from a mix of materials we have already created, web resources, and will be
backed up with coach-led sessions throughout the week.

## Basic Javascript

Start with this section if you feel like your understanding of Javascript loops,
functions, or objects is at 8/10 or less. You can work through from start to
finish or pick a point in the middle.

1. [Running Javascript](./js_bites/01_running_javascript.md)
2. [Running Files](./js_bites/02_running_files.md)
3. [Variables and Visibility](./js_bites/03_variables_and_visibility.md)
4. [Functions](./js_bites/04_functions.md)
5. [Conditionals](./js_bites/05_conditionals.md)
6. [Loops](./js_bites/06_loops.md)
7. [Functions as Values](./js_bites/07_functions_as_values.md)
8. [Callbacks](./js_bites/08_callbacks.md)
9. [Arrays](./js_bites/09_arrays.md)
10. [Objects](./js_bites/10_objects.md)
11. [Array Operations](./js_bites/11_array_operations.md)
12. [Classes](./js_bites/12_classes.md)

## Node, Express, and MongoDB Project

This is a small project to create a back-end web server using Node, ExpressJS,
and MongoDB.

Your challenge is to create an application for classified advertisements (like
Craigslist).

It should have two routes:

```plain
GET /adverts
# Should respond with this JSON
[
  { "title": "Selling a chair", "number": "07800000000" },
  { "title": "Seeking a table", "number": "07800000001" },
]
```

```plain
POST /adverts
# With data
{ "title": "Seeking a horse", "number": "07800000002" }
# Should respond with
{ "title": "Seeking a horse", "number": "07800000002" }
# And persist the new advert to the adverts collection in MongoDB
```

You will need to write tests in your job so we'll write them here too.

You can:

* Take on this project solo and use web documentation to tackle it. Or,
* Follow along with your coach who will demonstrate a portion of the application
  each day and give you some exercises to do.

## Gilded Rose

This is a project designed to train refactoring and software design skills.
Tackle it in a language you will be using on your placement period.

[The Gilded Rose Exercise](https://github.com/emilybache/GildedRose-Refactoring-Kata)

When you are done, send it to your coach who will provide code review.


<!-- BEGIN GENERATED SECTION DO NOT EDIT -->

---

**How was this resource?**  
[😫](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/js-mongo-catchup&prefill_File=README.md&prefill_Sentiment=😫) [😕](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/js-mongo-catchup&prefill_File=README.md&prefill_Sentiment=😕) [😐](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/js-mongo-catchup&prefill_File=README.md&prefill_Sentiment=😐) [🙂](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/js-mongo-catchup&prefill_File=README.md&prefill_Sentiment=🙂) [😀](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/js-mongo-catchup&prefill_File=README.md&prefill_Sentiment=😀)  
Click an emoji to tell us.

<!-- END GENERATED SECTION DO NOT EDIT -->
