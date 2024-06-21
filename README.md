# How-to-customize-the-dropdowns-placement-in-DOTNET-MAUI-AutoComplete-SfAutoComplete
This repository contains a sample demonstrating of customizing the dropdown's placement in .NET MAUI AutoComplete
## DropdownPlacement support in .NET MAUI Autocomplete (SfAutocomplete)
 We can change the dropdown's position in SfAutoComplete by changing the DropdownPlacement value.

The following code example illustrate how to set DropdownPlacement in SfAutocomplete.

**XAML**
```
<editors:SfAutocomplete DropDownPlacement ="Auto"
                        HeightRequest="40"
                       WidthRequest="200">
    <editors:SfAutocomplete.ItemsSource>
        <x:Array Type="{x:Type x:String}">
            <x:String>Telegram</x:String>
            <x:String>Televzr</x:String>
            <x:String>Tik Tok</x:String>
            <x:String>Tout</x:String>
            <x:String>Tumblr</x:String>
            <x:String>Twitter</x:String>
        </x:Array>
    </editors:SfAutocomplete.ItemsSource>
</editors:SfAutocomplete>

```



