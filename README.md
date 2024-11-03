# TDS-Project-1
**Project Overview**

This project retrieves and analyzes data on GitHub users based in Stockholm who have over 100 followers. Using the GitHub API, we collected and processed user information, as well as data on up to 500 of each user’s most recent public repositories. The results are provided in CSV files and summarized for easy analysis.




# **How the Data Was Collected:** 

**User Search:** Using GitHub’s search API, we retrieved users located in Stockholm with over 100 followers. For each user, additional profile information was fetched

**Repository Fetching:** For each user, up to 500 of the most recently pushed public repositories were collected.

**Data Cleaning:** Certain fields, like company, were cleaned for consistency. Leading @ symbols were removed, and company names were capitalized.

**Saving Data:** Data was saved in CSV format as users.csv and repositories.csv.


# **Key Insights and Analysis:**

Analyzing this dataset revealed interesting patterns:

**Popular Languages:** Python, JavaScript, and TypeScript were among the most common languages used by Stockholm-based developers.

**Open-source Activity:** A significant portion of users are actively contributing to open-source projects, with many repositories having a substantial number of stars and followers.

**Company Affiliations:** Several users are affiliated with leading technology companies or well-established startups, contributing regularly to high-profile projects.

# **Recommendations for Developers**

Based on the findings, here are some actionable insights for developers:

**Focus on Popular Languages:** Developers interested in networking with Stockholm-based GitHub users should consider projects in Python, JavaScript, or TypeScript, as these languages are prevalent within the community.

**Open-source Contributions:** Engaging in open-source projects could increase visibility and followers, especially given the high engagement with open-source seen in the Stockholm developer community.



