# XML
<?xml version="1.0" encoding="utf-8"?>
<ContentPage xmlns="http://xamarin.com/schemas/2014/forms" 
xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml" 
xmlns:local="clr-namespace:Project1O" 
xmlns:Views="clr-namespace:Project1O.Views; assembly=Project1O"
x:Class="Project1O.MainPage">
<ContentPage.BindingContext>
<Views:personView/>
</ContentPage.BindingContext>

<ListView ItemsSource="{Binding products}" 
HasUnevenRows="true">
<ListView.ItemTemplate>
<DataTemplate>
<ViewCell>
<StackLayout>
<Label Text="{Binding Name}"/>           
<Label Text="{Binding person}"/>  

<Button Text="Remove" BackgroundColor="Blue"
Command="{Binding remeoveCommand}"
Clicked="Remove_clicked" />
<Button Text="next" 
Clicked="Buttonclick"></Button>  


</StackLayout>


</ViewCell>
</DataTemplate>

</ListView.ItemTemplate>>

</ListView>
</ContentPage>
