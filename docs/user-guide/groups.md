---
layout: docwithnav
title: Device & Asset Groups
description: Device & Asset Groups Guide 

---

{% assign feature = "Device & Asset Groups" %}{% include templates/pe-feature-banner.md %}

* TOC
{:toc}

ThingsBoard allows you to configure multiple custom Device & Asset Groups. 
Each entity (device or asset) may belong to multiple groups simultaneously. 
Special group "All" always contains all devices that belong to specific tenant account.

For each entity group, ThingsBoard user may configure different columns to visualize specific telemetry or attributes values. 
ThingsBoard user may also define custom actions to be present for each entity: open dashboard or send RPC call, etc. 
Bulk operations to assign devices, add them to the group or remove are also supported.  
   
See video tutorial below for step-by-step instruction how to use this feature.

<br/>
<div id="video">  
    <div id="video_wrapper">
        <iframe src="https://www.youtube.com/embed/RNdaEqrGhn8" frameborder="0" allowfullscreen></iframe>
    </div>
</div> 

## Next steps

{% assign currentGuide = "AdvancedFeatures" %}{% include templates/guides-banner.md %}
