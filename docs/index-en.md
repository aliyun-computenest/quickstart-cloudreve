<h1>Cloudreve Community Edition Rapid Deployment </h1>

<h2> Overview </h2>

<p>Cloudreve allows you to quickly build a public-private network disk system. Cloudreve supports different cloud storage platforms at the bottom, users do not need to care about physical storage methods in actual use. You can use Cloudreve to build personal internet disks, file sharing systems, or public cloud systems for large and small groups. For more information, see <a href = "https://docs.cloudreve.org/">Cloudreve website </a>. </p>

<h2> Billing instructions </h2>

<p> The costs on the Cloudreve Community Edition are mainly related to:</p>

<ul>
<li> Selected vCPU and Memory Specifications </li>
<li> System disk type and capacity </li>
<li> Internet bandwidth </li>
</ul>

<h2> Permissions required for RAM accounts </h2>

<p> To deploy the Cloudreve Community Edition, you need to access and create some Alibaba Cloud resources. Therefore, your account must contain permissions for the following resources.
<strong> Note </strong>: This permission is required only when your account is a RAM account. </p>

<table>
<thead>
<tr>
<th> Permission policy name </th>
<th> Remarks </th>
</tr>
</thead>
<tbody>
<tr>
<td>AliyunECSFullAccess</td>
<td> Permissions to manage ECS </td>
</tr>
<tr>
<td>AliyunVPCFullAccess</td>
<td> Permissions for managing VPC networks </td>
</tr>
<tr>
<td>AliyunROSFullAccess</td>
<td> Manage permissions for Resource Orchestration Services (ROS) </td>
</tr>
<tr>
<td>AliyunComputeNestUserFullAccess</td>
<td> Manage user-side permissions for the compute nest service (ComputeNest) </td>
</tr>
</tbody>
</table>

<h2> Deployment process </h2>

<ol>
<li><p> Visit the Cloudreve community service <a href = "https://computenest.console.aliyun.com/service/instance/create/cn-hangzhou?type=user&ServiceId=service-a47e56f0ea9f460d8d33"> Deployment link </a> and fill in the deployment parameters as prompted:
<img src="en_1.jpg" alt="image.png" /></p></li>
<li><p> after the parameters are filled in, you can see the corresponding inquiry details. after confirming the parameters, click <strong> next: confirm the order </strong>. Confirm that the order is complete and agree to the service agreement and click <strong> Create Now </strong> to proceed to the deployment phase. </p></li>
<li><p> After the deployment is completed, enter the service instance management and find the Cloudreve service access link in the console.
<img src="en_2.jpg" alt="image.png" /></p></li>
<li><p> Click the link to access the service.
<img src="3.jpg" alt="image.png" /></p></li>
</ol>