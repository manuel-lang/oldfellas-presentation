# oldfellas-presentation

You might want to use the minified versions. You can create a minified version of the presentation using HTML minifiers such as [this](http://minifycode.com/html-minifier/) one.

## Ready to use version

Please see it [here](https://raw.githubusercontent.com/manuel-lang/oldfellas-presentation/master/v2/oldfellas.min.html).

## Update instructions

### Adding additional people to the presentation

Use the following template and fill out the information (CLAN_NAME, COUNTRY_CODE, CLAN_ID and USER_NAME)
```html
<tr>
  <td>
    <font size="2" color="#ef8caa">CLAN_NAME</font>
  </td>
  <td style="text-align: left">
    <font size="2" color="#8fb6b9">
      <img height="90%" src="http://www.cs-manager.com/images/flags/COUNTRY_CODE.png"/>
      <a style="text-decoration: none" href="http://www.cs-manager.com/csm/other/?p=other_info&s=clan&c=CLAN_ID"/>
          USER_NAME
    </font>
  </td>
</tr>
```

Then paste the block after [this line](https://github.com/manuel-lang/oldfellas-presentation/blob/675bd9feb909d2733d1d8f476421845968decc96/v2/oldfellas.html#L227).

### Updating trophies

Add a line with the trophy image source and the user as title attribute in the way as shown [here](https://github.com/manuel-lang/oldfellas-presentation/blob/2f38238841db646a7126e65d29c470a8a1ac05bd/v2/oldfellas.html#L246).
