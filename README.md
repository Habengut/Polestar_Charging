**Project Title**
Home Assistant Blueprint with notification for charging completed

**Description**
A Home Assistant Blueprint with notification for charging completed.

**Installing**
From Home Assistant, import the blueprint by adding the following url:
https://github.com/Habengut/Polestar_Charging/blob/main/Polestar_Charging_Blueprint.yaml

**Dependencies**
This Blueprint requires the Polestar_api from leeyuentuen:
https://github.com/leeyuentuen/polestar_api

**Customizing the notification**

Actions:
Send notification to your phone

Title:
Home Assistant

Message:
Your Polestar has finished charging

Tick the box "Data" and paste the following into the data field:

  notification_icon: mdi:car-side
  color: green
  visibility: public

**Help**
Any advise for common problems or issues.

**Author**
Habengut

**Version History**
1.0
Initial Release

**License**
This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details
