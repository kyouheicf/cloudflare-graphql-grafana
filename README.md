# cloudflare-graphql-grafana

1. Prepare your Grafana environment
   - Create free Grafana Cloud account
     - [Grafana Pricing | Free, Pro, Advanced, Enterprise](https://grafana.com/pricing/?tab=free%EF%BC%89)
   - or Use your own Grafana instance
2. Install and Configure GraphQL Data Source plugin
   - [GraphQL Data Source plugin for Grafana | Grafana Labs](https://grafana.com/grafana/plugins/fifemon-graphql-datasource/)
   
   ![graphql-datasource](https://qiita-user-contents.imgix.net/https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fkyouheicf%2Fimage%40master%2FuPic%2Fimage-20230216173434257.png?ixlib=rb-4.0.0&auto=format&gif-q=60&q=75&w=1400&fit=max&s=ba1f537487f52dcb6035176eb6f38738)
   
3. Import dashboard from JSON file
   - Ref. [Manage dashboards | Grafana documentation](https://grafana.com/docs/grafana/latest/dashboards/manage-dashboards/#import-a-dashboard)
4. Enter your `accountTag` or `zoneTag` as Textbox variable on dashboard in order to show your account (or zone) specific analytics data

![accountTag](https://qiita-user-contents.imgix.net/https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fkyouheicf%2Fimage%40master%2FuPic%2Fimage-20230216174208651.png?ixlib=rb-4.0.0&auto=format&gif-q=60&q=75&w=1400&fit=max&s=3d25ec9c4e54c0c5234db85d25dc2f2d)

## Other Example

<img width="1727" alt="image" src="https://user-images.githubusercontent.com/85217388/221065938-b9b3d3d2-a0de-48e2-8e44-f3440eea70e5.png">
