# CareerCrawler
Automated Research Internship &amp; RA Opportunities Finder

Overview

This project provides an automated solution to efficiently identify and compile research internships and remote research assistant (RA) opportunities specifically tailored for master's students. By leveraging web scraping and data extraction techniques, our system addresses common challenges faced by students seeking valuable academic experiences.

Problem Statement

Master’s students often struggle with:

Information Overload: Opportunities scattered across multiple platforms.

Time Sensitivity: Short-lived postings that close quickly.

Quality Filtering: Difficulty in manually sorting opportunities from top-ranked institutions.

Our Solution

Automated Web Scraping: Uses Google Search API to collect job listings directly from university websites.

Reddit Data Extraction: Employs Reddit API (AsyncPRAW) to fetch internship-related posts from relevant academic subreddits.

Ranking-based Filtering: Restricts results to QS 2025 top universities within specified regions.

Efficient Data Storage: Compiled results saved into structured CSV files for easy access and manipulation.

Technology Stack

Python

Requests: For handling HTTP requests and API interactions.

Pandas: For data processing and CSV management.

AsyncPRAW: For asynchronous data fetching from Reddit.

APIs:

Google Search API

Reddit API

Key Features

Daily Updates: Ensures up-to-date internship opportunities.

Keyword Filtering: Targets internships specifically related to economics and international relations.

Top University Focus: Prioritizes postings from prestigious QS-ranked universities.

Structured Accessibility: Results neatly organized into CSV format.

Impact

Our automated system significantly enhances academic and career development opportunities for master's students by:

Democratizing access to high-quality internships.

Saving considerable time spent searching manually.

Facilitating academic growth through accessible, timely opportunities.

Future Plans

Expanding the system to cover additional academic disciplines.

Developing a user-friendly web interface for easier access and visualization of opportunities.
