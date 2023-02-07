# Simon-Necktie Online Shopping Web Application
A fully featured online necktie shopping mall made using ASP.NET, C# 

<h2> List of Major Functions </h2> 
<table>
  <tr>
    <th>No</th>
    <th>Functions</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>1.</td>
    <td>Member Registration</td>
    <td>New or potential customers can register as a member through the registration form provided on the 'Register' webpage. Once registered, the customers shall have access to the member panel view of the website</td>
  </tr>
  <tr>
    <td>2.</td>
    <td>Adminstrative Functions</td>
    <td>The admin shall have access to the admin panel view of the website, allowing the admin to perform various administrative functions. The functions include managing users, products, offers, orders, payments, enquiries, and feedback.</td>
  </tr>
  <tr>
    <td>3.</td>
    <td>Products and Offer Catalogue</td>
    <td>The users/ customers of the Simon Necktie website can browse the products and offers catalogue. On the other hand, the admin can manage the products and offers catalogue by adding, deleting and editing the details of the products and offers.</td>
  </tr>
  <td>4.</td>
    <td>Shopping Cart</td>
    <td>Upon adding the products and offers to the cart, the users of the Simon Necktie website are required to register if they are not a member of the website. Once registered, they can view the list of products and offers added to the cart before making any payments.</td>
  </tr>
  <td>5.</td>
    <td>Payment Support </td>
    <td>Two payment methods options are allowed, including credit card
payment and cash on delivery. The customers are allowed to
download and print the transaction document, which contains the
details of the transactions. Accordingly, the website administrator
may update the order payment status on their admin panel's web
pages.</td>
  </tr>
   <td>6.</td>
    <td>Product Delivery </td>
    <td>Once the customers successfully make the payment, the product(s)
will be delivered to the customer based on the delivery address
inputted by the customer. Where there are any changes to the
product delivery details (e.g., delivery address), the website
administrator can manage the payments form and update the
details accordingly. The admin can also control the orders by
updating the order status of the products (i.e., pending, shipping
and delivered). </td>
  </tr>
     <td>7.</td>
    <td>Customer Enquires and Feedback </td>
    <td>Users/ customers who have any enquiries or looking for support
can leave their queries in the enquiry form on the 'Contact Us' web
page. They can also leave their feedback and comments through
the 'Feedback' web page's feedback form. What will follow is that
the administrator will view, check and take actions accordingly
based on the enquiry and feedback report generated in the system.
Once actions are taken, they can update the system accordingly
from 'pending' to 'resolved'.</td>
  </tr>
</table>

<h2> Site Structure Design </h2>

![SiteStructureDesign](https://user-images.githubusercontent.com/82561944/217253949-ca66bbba-c1e8-41c4-9762-6e2b00636368.png)


<h2> Summary of Set-Up and Configuration </h2>
To set up and configure the Simon Necktie website successfully, below is the list of items that
should be installed. <br>
1. Visual Studio 2019 (VS 2019)  <br>
➢ Download the Simon Necktie (IA-012022) folder  <br>
➢ Launch the VS code  <br>
➢ Select File > Open > Website > Select the downloaded Simon Necktie (IA-012022)
folder  <br> <br>
2. NuGet Packages <br>
➢ Right-click Simon Necktie (IA-012022) in the Solution Explorer <br>
➢ Select Manage NuGet Packages <br>
The list of NuGet Packages installed during the implementation of the website includes: <br>
- BouncyCastle Version 1.8.9 <br>
- iTextSharp Version 5.5.13.3 <br>
- ReportControlViewer Version 14.0.314.76 <br>
- Microsoft.SQLServerTypes Version 14.0.314.76 <br> <br>
Once the above are installed, the Simon Necktie website can be executed simply by clicking 
the IIS Express.  <br>

<h2> Interface </h2>
Below are some screenshots of the web application

<h3> Default HomePage </h3>

![HomePage](https://user-images.githubusercontent.com/82561944/217251016-54e0d1da-da66-43cd-9f93-27e1f7452fe1.png)

<h3> Login Page </h3>

![LoginPage](https://user-images.githubusercontent.com/82561944/217250902-a0dd33da-9adf-41fa-8439-4761d836a3cf.png)

<h3> Registration Page </h3>

![RegistrationPage](https://user-images.githubusercontent.com/82561944/217250911-9166e830-1bfc-49e0-8b29-0628101c29a0.png)

<h3> Detailed Product Description Page </h3>

![DetailedProductDescriptionPage](https://user-images.githubusercontent.com/82561944/217251038-aa1c2ee6-1f86-42db-97c8-50030b6bdb9b.png)

<h3> View Shopping Cart </h3>

![ViewShoppingCart](https://user-images.githubusercontent.com/82561944/217251059-94e94b34-f5d4-4e20-a19f-53fe305d38fd.png)

<h3> Make Payments </h3>

![MakePayments](https://user-images.githubusercontent.com/82561944/217251086-cf798542-7d82-441f-817a-60a9d5ca7acf.png)

<h3> View Shopping History </h3>

![ViewShoppingHistory](https://user-images.githubusercontent.com/82561944/217251116-03a6b3d7-1055-419a-a24a-7dfa8cbad174.png)

<h3> Print Transaction Details </h3>

![ReportPage](https://user-images.githubusercontent.com/82561944/217251154-8fd7d739-2713-4319-bc70-8df5ece8aa56.png)






