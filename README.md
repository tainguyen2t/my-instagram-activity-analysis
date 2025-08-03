# My Instagram Activities

This project dives deep into **my Instagram footprint** from 2015 to the present day.  
From `likes` to late-night `DMs` 🤡, it aims to uncover patterns in how I post, react, connect and sometimes overshare 🤦‍♂️.

## Project information
- **Conducted by**: Tai Nguyen *(tainguyen0604@gmail.com)*
- **Period**: Jul 29th – Aug 03rd, 2025 *(Data pulled from Instagram export – timestamp normalized to UTC+7)*
- **Contribution breakdown:**
     | Source             | Description                                                    | %     |
     |--------------------|----------------------------------------------------------------|-------|
     | **Self-conducted** | Data cleaning, plotting, existential reflection (with caffeine)| 70%   |
     | **AI-assisted**    | That cursed JSON read, Pandas datetime surgery, markdown therapy| 20%   |
     | **Google research**| *“How to fix matplotlib colormap that looks like clown vomit”*   | 10%   |
     > **Behind the scenes**: That one `.json` file parse nearly sent me into a midlife crisis at 29.

## Project objectives
1. **Review my entire Instagram activity history** since 2015
2. Discover **insights and behavior patterns** from posts, comments, likes and DMs
3. Analyze **follower/following relationships** over time
4. Identify **top interactions**: who I engage with the most and when
5. Visualize my usage by **year, month, hour** across different content types

## Contents
- `notebooks/my-instagram-activity-20250729.ipynb`: main notebook containing the full analysis
- `outputs/images/`: saved visualizations showing trends and summaries
- `outputs/insight-summary-no-comment.md`: key behavioral stats and social patterns
- `requirements.txt`: Python packages used in the project
- `README.md`: project overview and usage guide (you're reading it)

## Tools used
- **Python**: `ipython`, `nbformat`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `re`, `json`, `os`, `zoneinfo`
- **Jupyter Notebook**
- Data exported from **Instagram's account download tool**

## Notes
- All data used is **personal and anonymized** where needed.
- Timezones were adjusted using `zoneinfo` for accurate timestamp mapping.
- Includes full handling of comments, archived posts, inbox history, followers and stories.
- Not intended for performance optimization (unlike FPL 😅), but rather **self-reflection through data**.

---
> *"According to this dataset, I’ve been cringe since 2016. But statistically consistent. Fckin 🤡!" – me, after 3 hours of JSON debugging*   
> *"Statistically speaking, I’ve ghosted more people than I’ve posted 💀."*
