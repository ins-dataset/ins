---
sort: 1
---
# Download

Users are strongly recommended to read through the [User Manual](UserManual). It will help clarify some technical details that can help avoid unnecessary errors when dealing with multi-modal data.

## Calibration

The calibrated parameters for the sensorsuites are provided in the following yaml files:

[Robot Type 1]() (for **robot Type1* sequences)

[Robot Type 2]() (for **robot Type1* sequences)

## Single-Agent Scenes
The sequences are captured as rosbags, which are then compressed with bz2 method. User can uncompress the rosbags for less CPU usage at the cost of 3x memory storage. For user convenience, we extracted data from the rosbag, primarily providing color and depth images, lidar points as PCD files, and IMU.


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-mypc{background-color:#ffffff;color:#330001;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table border="1" class="tg" style="undefined;table-layout: fixed;text-align:center">
  <colgroup>
		<col style="width: 8px">
		<col style="width: 150px">
		<col style="width: 420px">
		<col style="width: 150px">
		<col style="width: 150px">
		<col style="width: 100px">
		<col style="width: 100px">
	</colgroup>
	<thead>
    <tr style="text-align: right;">
      <th class="tg-mypc"><span style="font-weight:bold">#</span></th>
      <th class="tg-mypc"><span style="font-weight:bold">SeqID</span></th>
      <th class="tg-mypc"><span style="font-weight:bold">Ground Truth</span></th>
      <th class="tg-mypc"><span style="font-weight:bold">Color Image</span></th>
      <th class="tg-mypc"><span style="font-weight:bold">Depth Image</span></th>
      <th class="tg-mypc"><span style="font-weight:bold">Livox</span></th>
      <th class="tg-mypc"><span style="font-weight:bold">Imu</span></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th class="tg-mypc"><span style="font-weight:bold">1</span></th>
      <td><a href="" rel="noopener noreferrer" target="_blank">indoor_long_corridor01 </a> </td>
      <td><a href=""> <img src="images/gtpreview/indoor1.png" title="Indoor_Long_Corridor1" alt="Indoor_Long_Corridor1"></a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Color</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Depth</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Lidar</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Imu</a></td>
    </tr>
    <tr>
      <th class="tg-mypc"><span style="font-weight:bold">2</span></th>
      <td><a href="" rel="noopener noreferrer" target="_blank">indoor_long_corridor02 </a> </td>
      <td><a href=""> <img src="images/gtpreview/indoor2.png" title="Indoor_Long_Corridor2" alt="Indoor_Long_Corridor2"></a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Color</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Depth</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Lidar</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Imu</a></td>
    </tr>
    <tr>
      <th class="tg-mypc"><span style="font-weight:bold">3</span></th>
      <td><a href="" rel="noopener noreferrer" target="_blank">indoor_long_corridor03 </a> </td>
      <td><a href=""> <img src="images/gtpreview/indoor3.png" title="Indoor_Long_Corridor3" alt="Indoor_Long_Corridor3"></a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Color</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Depth</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Lidar</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Imu</a></td>
    </tr>
    <tr>
      <th class="tg-mypc"><span style="font-weight:bold">4</span></th>
      <td><a href="" rel="noopener noreferrer" target="_blank">indoor_long_corridor04 </a> </td>
      <td><a href=""> <img src="images/gtpreview/indoor4.png" title="Indoor_Long_Corridor4" alt="Indoor_Long_Corridor4"></a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Color</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Depth</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Lidar</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Imu</a></td>
    </tr>
  </tbody>
</table>

## Multi-Agent Scenes
The multi-agent scenario consists of four trajectories within the long_corridor scene, each containing segments with inter-agent loop closures.
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-mypc{background-color:#ffffff;color:#330001;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table border="2" class="tg" style="undefined;table-layout: fixed;text-align:center">
  <colgroup>
		<col style="width: 150px">
		<col style="width: 420px">
		<col style="width: 150px">
		<col style="width: 150px">
		<col style="width: 100px">
		<col style="width: 100px">
	</colgroup>
	<thead>
    <tr style="text-align: right;">
      <th class="tg-mypc"><span style="font-weight:bold">SeqID</span></th>
      <th class="tg-mypc"><span style="font-weight:bold">Ground Truth</span></th>
      <th class="tg-mypc"><span style="font-weight:bold">Color Image</span></th>
      <th class="tg-mypc"><span style="font-weight:bold">Depth Image</span></th>
      <th class="tg-mypc"><span style="font-weight:bold">Livox</span></th>
      <th class="tg-mypc"><span style="font-weight:bold">Imu</span></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="" rel="noopener noreferrer" target="_blank">Multi-agent_long_corridor </a> </td>
      <td><a href=""> <img src="images/gtpreview/indoor1.png" title="Indoor_Long_Corridor1" alt="Indoor_Long_Corridor1"></a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Color</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Depth</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Lidar</a></td>
      <td><a href="" rel="noopener noreferrer" target="_blank">Imu</a></td>
    </tr>
  </tbody>
</table>