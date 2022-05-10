# prettyJson Pipe

**You can use this pipe like:**\
`<pre [innerHtml]="YOUR_JSON | prettyJson: [true, 3]"></pre>`\
\
**prettyJsonPipe default values** are '*false*' for line numbers and *3* for paddings. \
\
The difference between `<pre>{{YOUR_JSON | json}}</pre>` and this pipe; You can add line numbers and you have a CSS file colored by value types like string, number and bool.

### Example output is:
![Example Output](https://github.com/cmoztas/Angular-Pretty-Json-Pipe/blob/main/ex.png?raw=true "Example Output")

##### Live Example
http://my-angular-tests.herokuapp.com/ 

##### Source
https://stackoverflow.com/questions/37308420/
