# Google Trends analyser

Use the [Excel analysis workbook](google-trends-analysis.xlsx) to explore one
search term in Google Trends and record the evidence and your reflections. The
workbook contains input sheets and a formula-driven summary; it does not fetch
data from Google.

## Collect and enter data

1. Open [Google Trends Explore](https://trends.google.com/trends/explore) and
   enter a search term or select a topic. Choose the geography, time range,
   category and search type that fit your question. Record these settings and
   the export date on the **Summary** sheet. Keep them consistent for all
   exports.
2. Download the CSV files for interest over time and interest by region. For
   related topics and related queries, select **Top** and **Rising** in turn
   and download each view. Availability depends on the term and settings.
3. Open each CSV in Excel. Copy the data rows only, not the title or column
   headings, and paste **values** into the matching workbook sheet starting
   at cell A2. Use the columns below; preserve the order supplied by Google.
   Do not paste over the Summary formulas. Keep each sheet's rows contiguous.

   | Workbook sheet | Columns to paste in order |
   | --- | --- |
   | Over time | Period, interest |
   | By region | Region, interest |
   | Top topics | Topic, type, value |
   | Rising topics | Topic, type, value |
   | Top queries | Query, value |
   | Rising queries | Query, value |

   CSV headings and layouts can vary by language, settings and export. Select
   and reorder the relevant columns if necessary. Retain period labels exactly
   as exported, including date ranges. If a view has no data, leave its sheet
   empty. The template supports **1,000 data rows per sheet**; summary formulas
   do not include rows beyond row 1001. Save a separate copy for each analysis.
4. Review the **Summary** and complete the prompts on **Reflection**. The
   summary shows counts, the average and peak numeric interest over time, the
   highest numeric regional interest, and the first item in each related list.
   The latter assumes that the exported list is ordered by Google.

## Interpreting the results

- Interest scores are relative, normalised values from 0 to 100, not search
  volumes. A score of 100 represents the peak within the relevant selection;
  regional scores describe relative popularity within each region, not total
  searches. Do not compare independently scaled exports as absolute volumes.
- Google may display values such as `<1` or `Breakout`. Preserve them as text:
  the numerical averages and peaks exclude non-numeric entries. The summary
  reports their count for the time and regional sheets. Rising values describe
  growth rather than the interest index used in top lists.
- Results can be sampled, change over time, or be unavailable for low-volume
  searches. Note partial periods, missing data, significant events and other
  limitations before drawing conclusions. A trend is not proof of causation.

For further details, see [Google's guide to Trends data](https://support.google.com/trends/answer/4365533).
