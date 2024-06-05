---
layout: page
title: ReadMe
permalink: /readme/
---

### Adding a Post
Create a new markdown file in the '_posts' directory, ensuring the filename follows this format:

```
YYYY-MM-DD-quick-title.md
```

The 1st few lines of the page should be like this:
```
---
layout: post
author: <AUTHOR_NAME>
title: <DISPLAYED_TITLE>
---
```

### Adding/Editing Training
In the '_data' directory, you will find a 'training.yml' file. You can either add a new entry or 
edit an existing one. Each entry should be formatted as follows:

```
- title: Nanopore Sequencing & Data Analysis
  subtitle: Learn about nanopore sequecning and data analysis by performing your own 16S sequecning experiement!
  description: Learn - The science behind nanopore sequencing, How to prepare a 16S amplicon library for sequencing, Loading a library onto a MinION flow cell, Sequencing on the MinION platform, Basics of nanopore data, Analysis of our 16S data using Galaxy
  date: 10-06-2024
  duration: 1
  institute: ATBU
  city: Bauchi
  location: ATBUTH
  link: https://atbu.edu.ng
```

### Adding/Editing Members
In the '_data' directory, you will find a 'members.yml' file. You can add a new entry 
using the existing ones as a template or make edits as required.

Each entry should be formatted like this (omit the GitHub line if you don't have one):

```
- name: Umar Ahmad
  github: babasaraki
  institute: Molecular Genetics Informatics, Bauchi State University
  email: umarahmad@basug.edu.ng
  website: https://africacdc.org/institutes/ipg/
  twitter: babasaraky
  interests: Cancer, RNA-Seq, WGS, WES, Microarrays, AI/Machine learning.
```

### Adding/Editing Meetings
In the '_data' directory, you'll find a 'meetings.yml' file. You can add a new entry 
using the existing ones as a template or make edits as required. Meetings will automatically 
appear in the "Past" section if their date is before today's date.

Each entry should be formatted as follows:
```
- meeting: Genomics Africa |2
  theme: Cancer Genomics and Precision Oncology Care
  month: June
  day: 5
  year: 2024
  institute: National Institute for Cancer Research and Treatment
  city: Abuja
```

### Adding/Editing A Meeting Page
Add a page in the format `northernbug2.md` to the folder `meeting_details`this should have the following format:

```
---
layout: meeting
author: <MEETING_HOSTS>
title: <MEETING_TITLE>
date: <DATE>
institute: <INSTITUTE>
postcode: <VENUE_POSTCODE>
address: <FULL_VENUE_ADDRESS>
permalink: <FILENAME_WITHOUT_.md> 
---

# General

# Agenda

| Time          | Speaker        | Presentation | Information |
|---------------|----------------|--------------|-------------|
| 12:00-13:00   | Lunch          |              |             |
| 13:00-14:30   | Session 1      |              |             |
| 14:30-15:00   | Coffee         |              |             |
| 15:00-16:00   | Session 2      |              |             |
| 16:00-17:00   | Discussion/Pub |              |             |


# Registration

# Attendees

```

### Meeting Sign-Up
Meeting sign-up is managed via Google Forms. We have customized the field names 
and action to create our own form. Responses are collected in a Google Sheet.

When a meeting registration closes, we create a new tab and keep 
the sign-up list from previous meetings in their respective tabs.
