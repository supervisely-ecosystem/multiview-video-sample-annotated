<div align="center" markdown>

<img src="https://i.imgur.com/UdBujFN.png" width="250" /> <br>

# Multiview Video Sample Annotated

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#download">Download</a>
</p>

[![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervisely.com/slack)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/supervisely-ecosystem/multiview-video-sample-annotated)
[![views](https://app.supervisely.com/img/badges/views/supervisely-ecosystem/multiview-video-sample-annotated.png)](https://supervisely.com)
[![downloads](https://app.supervisely.com/img/badges/downloads/supervisely-ecosystem/multiview-video-sample-annotated.png)](https://supervisely.com)

</div>

## Overview

This is a multiview project video sample consisting of four videos, each representing a different camera view.. The project demonstrates multi-camera video annotation capabilities in Supervisely platform.

The dataset consists of 4 synchronized video streams from different camera viewpoints (synchronization achieved using time offset), video annotations with polygon shapes for object tracking, metadata files containing camera and video information.

### Annotation Details

The project was annotated using SAM3 (Segment Anything Model 3) for precise object segmentation and AutoTrack for automated object tracking across video frames.

### Classes and Tags

The project includes 2 object classes: `box` for annotating boxes and `chalk` for annotating chalk objects. Additionally, there is 1 object tag `color` - a tag for additional color-based object properties.

<img src="https://github.com/supervisely-ecosystem/multiview-video-sample-annotated/releases/download/v1.0.0/screenshot-dev-internal-supervisely-com-app-videos_v3-1768485576526.png" />

## Download

Multiview project sample in Supervisely format (88.6 MB): [Download ZIP archive](https://github.com/supervisely-ecosystem/multiview-video-sample-annotated/releases/download/v1.0.1/project.zip)
