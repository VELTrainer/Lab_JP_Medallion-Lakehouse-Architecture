---
title: Introduction to the Medallion Lakehouse Architecture 🥉🥈🥇
permalink: index.html
layout: home
---
# 🏅 About the Medallion Architecture 🏠

The Medallion Lakehouse Architecture (commonly referred to as the "Medallion Architecture") is a layered approach to organizing data in a lakehouse. See the Microsoft documentation here: ["Medallion architecture"](https://learn.microsoft.com/ja-jp/azure/databricks/lakehouse/medallion).

[The Medallion Architecture consists of three distinct layers (zones). Each layer represents a different level of data quality stored in the lakehouse...]
  
An important point is that the Medallion Architecture ensures atomicity, consistency, isolation, and durability (ACID) as data moves through the layers. Raw data...

The goal of this exercise is to build the Fabric architecture hands-on and share it within your group.
Because diagrams are created by people with different styles and preferences, visual variations in the diagrams are natural.
What matters most is that you deepen your own understanding of Fabric.

# ☁️ About Azure Diagrams ☁️

In this exercise we will use the free tool Azure Diagrams to create diagrams that explain the Fabric architecture.

Azure Diagrams is not an official Microsoft product. It is a helpful community resource created by Microsoft employees to illustrate architectures.
There is no cost to use it, but please follow your organization's security and compliance policies when deciding whether to create an account.
For today's exercise you can complete all tasks without an account, so creating one is optional.

## Accessing and preparing Azure Diagrams

First, open the following link in a separate browser tab.
Click "Blank Canvas".

<!-- This link format lets us open in a seperate tab 😇 -->
<a href="https://azurediagrams.com/" target="_blank">https://azurediagrams.com</a>

<img src="images/AZD1.png" alt="Azure Diagrams main screen" style="width:950px; height:500px;">

## Tool guide and explanation

How to use 1️⃣: Top-right controls

1. New Diagram: Create a new canvas. If you press New Diagram without saving the diagram in progress, the unsaved work will be lost.
2. Clone Diagram: Duplicate the current diagram to a new link.
3. Export: Export the diagram as an image.
4. Settings: Various settings for your profile and diagram.
5. Save Changes: Changes are not auto-saved, so press this before closing.
6. Profile: (Optional) Sign in to an account, edit your profile, or change your password.

<img src="images/AZD2.png" alt="Azure Diagrams Tutorial" style="width:950px; height:500px;">

How to use 2️⃣: Left-side palette

1. Search: Search common services and add them to the diagram. Not all resources are shown.
2. Annotation: Add a large text label for longer explanations.
3. Label: Add a short text label.
4. Custom Resource: Create a custom tile for products or processes. It includes an icon, title, and subtitle.
5. Section: Group multiple resources inside a box.
6. Shape: Create shapes for the diagram.

<img src="images/AZD3.png" alt="Azure Diagrams Tutorial" style="width:950px; height:500px;">

How to use 3️⃣: Custom Resource

1. Custom Resource: Drag and drop to add a custom resource to the canvas.
2. Connections / Data Flow: Draw lines between Custom Resources to show data flow. Depending on resource types, connector styles may change automatically.
3. Customization: Click the icon to adjust how the Resource tile is displayed.
4. Icons: There are many icons that do not appear in Search. Use them if you want more detailed architecture diagrams.

<img src="images/AZD4.png" alt="Azure Diagrams Tutorial" style="width:950px; height:500px;">

How to use 4️⃣: Custom Shapes

1. Shapes: Drag and drop shapes onto the canvas.
2. Shape: Choose the shape type.
3. Background Color: Increase transparency to make the shape outline-only.
4. Border Color: Set the border color for the shape.

<img src="images/AZD5.png" alt="Azure Diagrams Tutorial" style="width:950px; height:500px;">

### Optional: Account registration

This exercise can be completed without registering an account.
However, if you choose to create an account, the benefits include:
- Save diagrams and edit them later
- Share diagrams with others or the community
- Share private diagrams with specific users and set access roles

How to sign up

1️⃣ Click "Sign In" at the top-right and then click "Sign in or Create Account"

<img src="images/AZD8.png" alt="Azure Diagrams screen" style="width:950px; height:500px;">

2️⃣ Click "Don't have an account? Sign up now"

3️⃣ Enter your email address on the next screen. After confirming your email, set a password and your display name.

<img src="images/AZD8-5.png" alt="Azure Diagrams sign up" style="width:950px; height:500px;">

# ✅ Review sample Fabric architecture diagrams ✅

**1️⃣** Click "Examples" at the bottom-left.

<img src="images/AZD10.png" alt="Azure Diagrams screen" style="width:950px; height:500px;">

**2️⃣** The Examples window opens. Drag the window by its top (1) to resize it.
Find and click the Fabric sample diagram "Lakehouse Architecture on Fabric" (2).

<img src="images/AZD11.png" alt="Azure Diagrams screen" style="width:950px; height:500px;">

**3️⃣** Hover over the connection between "Fabric Data Factory" and "Fabric Lakehouse" and confirm that the integration detail shows "Batch & Scheduled."

<img src="images/AZD12.png" alt="Azure Diagrams screen" style="width:950px; height:500px;">

**4️⃣** There are community-provided examples as well. Click "Community Diagrams", then use the browser find (Ctrl+F) to search "Fabric" and choose any sample you like.

<img src="images/AZD13.png" alt="Azure Diagrams screen" style="width:950px; height:500px;">

# 🏠 Create your Fabric architecture diagram 🌊

## Exercise

1. Use Azure Diagrams to create diagrams representing what you completed in labs 01–04.
2. (Optional) Clone the diagram from step 1 and reflect the content of labs 05–07.
3. Extend the lab 01–04 diagram to represent the Medallion architecture.

### Example answers

1. [Example for labs 01–04](./images/diagram-01-04.png) : [Azure Diagrams](https://azurediagrams.com/D54ivtsh)  
2. [Example for labs 05–07](./images/diagram-05-07.png) : [Azure Diagrams](https://azurediagrams.com/e4F4s7l8)  
3. [Example Medallion architecture diagram](./images/diagram-medallion.png) : [Azure Diagrams](https://azurediagrams.com/NhmRmML4)

# 📂 Exporting and sharing diagrams 🔗

How to share a diagram — two methods

Method 1️⃣: Save as an image

You can export PNG or SVG. Click the image icon at the top-right and choose the file type.

SVG preserves interactive elements (like scrollable areas).

<img src="images/AZD20.png" alt="Azure Diagrams export" style="width:950px; height:500px;">

Method 2️⃣: Share access to the diagram

There are three sharing types:
1. Community: The diagram is searchable and viewable by anyone and appears in Community Diagrams.
2. Link: The diagram is hidden from search but accessible to anyone with the unique link.
3. Private: Access is limited to the people you share it with.

To share, save the diagram and click the settings gear ⚙.

From settings, choose "Sharing" 👥.

<img src="images/AZD21.png" alt="Azure Diagrams sharing" style="width:950px; height:500px;">

## Resources

- [Implement a Medallion Lakehouse architecture with Microsoft Fabric](https://learn.microsoft.com/ja-jp/fabric/onelake/onelake-medallion-lakehouse-architecture)
- [Greenfield Lakehouse on Microsoft Fabric](https://learn.microsoft.com/ja-jp/azure/architecture/example-scenario/data/greenfield-lakehouse-fabric)
- [Microsoft Fabric Developer Guide (slides)](https://speakerdeck.com/ryomaru0825/microsoft-fabric-kai-fa-gaido?slide=31)
