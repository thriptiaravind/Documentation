# Setting up with Amazon EC2

Complete the tasks in this section to get set up for launching an Amazon EC2 instance for the first time:

1. [Sign up for AWS](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/get-set-up-for-amazon-ec2.html#sign-up-for-aws)
2. [Create a key pair](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/get-set-up-for-amazon-ec2.html#create-a-key-pair)
3. [Create a security group](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/get-set-up-for-amazon-ec2.html#create-a-base-security-group)

When you are finished, you will be ready for the [Amazon EC2 Getting started](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/EC2_GetStarted.html) tutorial.
___
## Sign up for AWS
When you sign up for Amazon Web Services (AWS), your AWS account is automatically signed up for all services in AWS, including Amazon EC2. You are charged only for the services that you use.

With Amazon EC2, you pay only for what you use. If you are a new AWS customer, you can get started with Amazon EC2 for free. For more information, see [AWS Free Tier](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc).

If you have an AWS account already, skip to the next task. If you don't have an AWS account, use the following procedure to create one.

**To create an AWS account**
1. Open [https://portal.aws.amazon.com/billing/signup](https://portal.aws.amazon.com/billing/signup).
2. Follow the online instructions.
Part of the sign-up procedure involves receiving a phone call and entering a verification code on the phone keypad.
___
## Create a key pair
AWS uses public-key cryptography to secure the login information for your instance. You specify the name of the key pair when you launch your instance, then provide the private key to obtain the administrator password for your Windows instance so you can log in using RDP.

If you haven't created a key pair already, you can create one using the Amazon EC2 console. Note that if you plan to launch instances in multiple Regions, you'll need to create a key pair in each Region. For more information about Regions, see [Regions and Zones](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/EC2Win_Infrastructure.html#EC2Win_Regions).
You can create a key pair using one of the following methods.


**Table 1**


| New Console | Old Console |
| --- | ---|
| **To create your key pair** | **To create your key pair** |
| ABC | Null |
| 123 | 456 |

1. In the navigation pane, choose **Key Pairs**.
2. Choose **Create key pair**.
3. For ***Name***, enter a descriptive name for the key pair. Amazon EC2 associates the public key with the name that you specify as the key name. A key name can include up to 255 ASCII characters. It can’t include leading or trailing spaces.
4. For ***File format***, choose the format in which to save the private key. To save the private key in a format that can be used with OpenSSH, choose pem. To save the private key in a format that can be used with PuTTY, choose ppk.
5. Choose **Create key pair**.
6. The private key file is automatically downloaded by your browser. The base file name is the name you specified as the name of your key pair, and the file name extension is determined by the file format you chose. Save the private key file in a safe place.
> Important
This is the only chance for you to save the private key file.

For more information, see [Amazon EC2 key pairs and Windows instances](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/ec2-key-pairs.html).

**Old Console**
1. Open the Amazon EC2 console at [https://console.aws.amazon.com/ec2](https://console.aws.amazon.com/ec2/).
2. In the navigation pane, under **NETWORK & SECURITY**, choose **Key Pairs**.
> Note
The navigation pane is on the left side of the Amazon EC2 console. If you do not see the pane, it might be minimized; choose the arrow to expand the pane.

3. Choose **Create Key Pair**.
4. For ***Key pair name***, enter a name for the new key pair, and then choose **Create**. The name can include up to 255 ASCII characters. It can’t include leading or trailing spaces.
5. The private key file is automatically downloaded by your browser. The base file name is the name you specified as the name of your key pair, and the file name extension is `.pem`. Save the private key file in a safe place.
> Important
This is the only chance for you to save the private key file.

## Testing Guthub Flavor

Your computer crashed? Try sending a 
<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd>.
~~It was created by John Gruber in 2004.~~


<table class="table table-striped">

<caption>Caption for this Table</caption>

<thead class="thead-dark">

<tr>
    <th width="30%">Property</th>
    <th width="70%">Description</th>
    </tr>
</thead>

<tbody>

<tr>
    <td>Topic1</td>
    <td>Topic2
        <ul>
        <li>Bullet item</li>
        <li>Bullet item</li>
        </ul>
        </td>
    </tr>

<tr>

   <td>TopicA</td>

<td>TopicB</td>

</tr>

</tbody>

</table>


![Image](/IMG_20200710_143116.jpg)
