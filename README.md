# NCHU WE-I Goose．Smith
## Smart elevator based on edge computing architecture combined with gesture recognition
## Introduction
This project combines the advantage of Himax WE-I Plus and NVIDIA Jetson Nano, which are low-power comsumptioned and high efficiency respectively.Using cygwin to transfer the pretrained model into the version of Tensorflow lite, then detecting the hand movement by Himax WE-I Plus, depend on NVIDIA Jetson Nano to process the gesture recognition, send the recognition output to the server to control the elevator. 
 
## Demo Video
## System architecture
<img src="https://user-images.githubusercontent.com/51142934/126688700-0d2efc21-179b-4a5f-b32e-562f179e645f.png" width="800" height="300">

## Required Hardware
<table>
  <tr>
    <td>Hardware</td>
  </tr>
 <tr>
    <td>HC-SR04</td>
  </tr>
  <tr>
    <tr>
    <td>Himax We-I Plus</td>
  </tr>
    <td>HDMI screen</td>
  </tr>
  <tr>
    <td>NVIDIA Jatson Nano</td>
  </tr>
  <tr>
    <td>Logitech Webcam</td>
  </tr>
  <tr>
    <td>AC8265 2.4G/5G WiFi BT4.2</td>
  </tr>
 
 </table>
 
## Required Software

<table>
  <tr>
    <td>Software</td>
    <td>Version</td>
  </tr>
  <tr>
    <td>distro-info</td>
    <td>0.18ubuntu0.18.04.1</td>
   </tr>
 <tr>
    <td>Jetson.GPIO</td>
    <td>2.0.17</td>
 </tr>
 <tr>
    <td>matplotlib</td>
   <td>2.1.1</td>
   </tr>
 <tr>
   <td>mediapipe</td>
   <td>0.8.5-cuda102</td>
   </tr>
 <tr>
   <td>numpy</td>
   <td>1.19.4</td>
   </tr>
 <tr>
   <td>opencv-contrib-python</td>
   <td>4.5.3.56</td>
   </tr>
 <tr>
   <td>pip</td>
   <td>21.1.3</td>
   </tr>
 <tr>
   <td>pyserial</td>
   <td>3.5</td>
   </tr>
 <tr>
   <td>python-apt</td>
   <td>1.6.5+ubuntu0.6</td>
   </tr>
   <td>requests</td>
   <td>2.18.4</td>
   </tr>
   <tr>
   <td>requests-unixsocket</td>
   <td>0.1.5</td>
  </tr>
</table>

## User guide

