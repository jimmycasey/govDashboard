# govDashboard.ie

## Government Dashboard was created to track the data that matters to people in Ireland.
![](screenshot_dashboard.png)
[govdashboard](https://jimmycasey.github.io/govDashboard/) is a crowdsourced, single source of truth for data points across:
- Housing
- Income
- Health

### How it works

- Anyone can make an update to the dashboard when new data becomes available. See "Contributing" below.
- All info in the dashboard is backed up with a link from a reputable source.
- All sources and history is available in the github repo along with who made the updates.

### Contributing

To update a metric, edit the json at the bottom of index.html by following the guide below or create a PR how you usually do:
- https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files#editing-files-in-another-users-repository
https://github.com/jimmycasey/govDashboard/blob/eec34cdc94f62e826408f93699d8ab6b860bc1d1/index.html#L137-L162

Or propose an update by creating a new issue here: https://github.com/jimmycasey/govDashboard/issues

### Under the Hood

- Built from static HTML, deployed using GitHub Actions and hosted in GitHub Pages.
- Tweets on every merge to main with "send-tweet-action" Github Action using the commit message as the tweet status.

### Thanks
- https://www.codinglabweb.com/2021/05/admin-dashboard-in-html-css.html
- https://boxicons.com/
- https://www.blacknight.com/
- https://github.com/marketplace/actions/send-tweet-action
