# XML
<?xml version="1.0" encoding="UTF-8"?>
<ContentPage xmlns="http://xamarin.com/schemas/2014/forms"
xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml" 
x:Class="Project1O.MyPage2"
BackgroundColor="Gray"
Title="second page">
<ContentPage.Content>

<StackLayout HorizontalOptions="Center" VerticalOptions="Center">
<Grid>
<Grid.RowDefinitions>
<RowDefinition Height="Auto"></RowDefinition>
<RowDefinition Height="Auto"></RowDefinition>
<RowDefinition Height="*"></RowDefinition>
</Grid.RowDefinitions>       
<Image Source="2.jpg"></Image>
</Grid>
<Label Text="Name:Owen"/>
<Label Text="Phone Number:1234567"/>
<Label Text="Email:1234567@deakin.edu.au"/>

</StackLayout>

</ContentPage.Content>
</ContentPage>

