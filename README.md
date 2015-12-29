# FoldingCell

[shot on dribbble](https://dribbble.com/shots/2121350-Delivery-Card):
![Animation](Screenshots/folding-cell.gif)

## Requirements

- iOS 8.0+
- Xcode 7.2

## Installation

Just add the FoldingCell.swift file to your project.

## Usage

1) Create a new cell inherit from FoldingCell

2) Add UIView to your cell in your storyboard or nib file, inherit it from RotatedView.
Connect the outlet from this view to the cell property "foregroundView".
Add constraints from this view to superview like a picture: 
![1.1](/Tutorial-resources/1.1.png)

(constants of constraints may be differents). Add identifier "ForegroundViewTop"
for top constraint. (This view will be show than cell is normal state).

3) Add other UIView to your cell, connect the outlet from this view to the cell
property "containerView". Add constraints from this view to superview like a picture:

![3.2](/Tutorial-resources/1.2.png)

(constants of constraints may be differents). Add identifier "ContainerViewTop" for top constraint.
(This view will be show than cell is open state)

Your result something like this picture:
![3.3](/Tutorial-resources/1.3.png)