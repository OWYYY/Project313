# XML
<?xml version="1.0" encoding="UTF-8"?>
<ContentPage xmlns="http://xamarin.com/schemas/2014/forms" xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml" x:Class="Project1O.login">
<ContentPage.Content>
<StackLayout Padding="100">

<Label x:Name="Lable_username" Text="username"/>

<Entry x:Name="Entry_username" Placeholder="username"/>

<Label x:Name="Lable_password" Text=" password"/>

<Entry x:Name="Entry_password" Placeholder="password"/>

<Button x:Name="Btn_sign" Text="Sign In" Clicked="SignIn"/>

</StackLayout>
</ContentPage.Content>
</ContentPage>
