# minicolors-angular

Minicolors-angular is an [AngularJS](http://angularjs.org/) directive for [jQuery MiniColors](http://labs.abeautifulsite.net/jquery-minicolors/).

## Usage

- add the minicolors-angular module to your app
- add attribute `minicolors` to an text input element
- specify options (see [MiniColors documentation](http://labs.abeautifulsite.net/jquery-minicolors/#settings)) by setting them as value of the minicolors attribute

### Example

```
<input type="text" ng-model="color" minicolors="{theme:'bootstrap',control:'wheel'}">
```
