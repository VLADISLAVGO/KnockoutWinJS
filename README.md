# KnockoutWinJS
Knockout extension for WinJS toolkit

#Dependencies:
1. __jQuery__ (v3.3.0) https://jquery.com
2. __KnockoutJS__ (v2.1.4) http://knockoutjs.com/downloads/index.html
3. __WinJS__ (v4.0.0-priview) http://try.buildwinjs.com/#get

#Intro
This extension defines __knockout bindings__ and register __knockout components__ for whole set of WInJS control. 
So WinJS controls can be bound to ViewModel not only in classical data-bind way, but in __XAML-like__ way (thanks to   
knockout components support) with declarative property definition: 

    <listview params="{layout: 'grid', itemsSource: $data.items}">
       <listview-itemtemplate>
          <div data-bind="text: $data.title"></div>
       </listview-itemtemplate>
       <listview-header>
          <div>Header</div>
       </listview-header>
       <listview-footer>
          <div>Footer</div>
       </listview-footer>
    </listview>
