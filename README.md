# uib-persian-datepicker

require https://angular-ui.github.io/bootstrap/

compatible uib v1.1.1

note: the type of model is string like '1394/11/29' not date!

getting started:

```html

<link href="/plugins/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet" type="text/css" />
<link href="/plugins/bootstrap/3.3.6/css/bootstrap-rtl.min.css" rel="stylesheet" type="text/css" />

<script type="text/javascript" src="/plugins/angularjs/1.4.8/angular.min.js"></script>
<script type="text/javascript" src="/plugins/ui-bootstrap/1.1.1/ui-bootstrap-tpls.min.js"></script>
<script type="text/javascript" src="persiandate.js"></script>
<script type="text/javascript" src="persian-datepicker-tpls.js"></script>

```

```html

<div class="input-group">
	<input type="text" name="date" class="form-control" persian-datepicker-popup="yyyy/MM/dd"  ng-model="date" is-open="datetopened" min-date="'50 years past'" max-date="'now'" />
	<span class="input-group-btn">
		<button type="button" class="btn btn-success" ng-click="datetopened=true"><i class="fa fa-calendar"></i></button>
	</span>
</div>

```
