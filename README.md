## About

`^(?:(.+)?\/|)(.+\.$|.+(?<!\.)(?=\.)|.+)?(?:\.(.+))?$`

Regex that cuts a resource path into its components.
- Robust: handles edge cases (screenshot).
- Performance: 20~100 steps, long and short paths ~equal time.
- Support: made to work with ECMAScript(JavaScript) and most other engines.

https://regex101.com/r/8aBZDd/5
<div>
    <img src="screenshots/001.png" alt="screenshot" width="auto" height="auto">
</div>
