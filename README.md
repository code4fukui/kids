# kids

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple web application to search and filter events for the 2017 "Children's Kasumigaseki Viewing Day" (こども霞が関見学デー), a public outreach event by Japanese government ministries.

**Live Demo:** [fukuno.jig.jp/1816](http://fukuno.jig.jp/1816)


![Application Screenshot](https://fukuno.jig.jp/img/kids2017.png)


## Features

- **Keyword Search:** Instantly search through all event details.
- **Filter by Category:** Narrow down events by type:
  - Learn (学ぶ), Touch/Feel (ふれる・感じる), Move Body (体を動かす), Play Music (奏でる), Ride (乗る), See (見る), Create/Draw (作る・描く), Harvest/Collect (収穫・採集する), Other (その他)
- **Filter by Target Audience:** Select the appropriate age group:
  - Pre-school (就学前), Lower Elementary (小学生低学年), Middle Elementary (小学生中学年), Upper Elementary (小学校高学年), Middle School (中学生), High School & Above (高校生以上)

## How It Works

This is a client-side application built with vanilla HTML, CSS, and JavaScript. It dynamically fetches program data from a public Google Sheet using a JSONP request to the Google Sheets API. The data is then parsed and rendered into a searchable, filterable list.

## Data Source

The application uses open data published for the 2017 event.

- **Source:** [平成29年度こども霞が関見学デー プログラムオープンデータ](https://docs.google.com/spreadsheets/d/1FEhoCeSrnW-D8YLSfy3wMD