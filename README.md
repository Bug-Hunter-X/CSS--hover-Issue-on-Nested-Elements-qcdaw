# CSS :hover Issue on Nested Elements

This repository demonstrates an uncommon CSS bug related to the `:hover` pseudo-class and nested elements.  In certain scenarios, hovering over a nested element unexpectedly triggers the `:hover` effect on its parent, leading to unexpected visual behavior.

## Problem

The provided CSS aims to change the background color of the outer `div` only when it's directly hovered over.  However, in some browsers or CSS implementations, hovering over the inner `div` also triggers the outer div's hover style. This is counter-intuitive and can cause unexpected user interactions.

## Solution

The solution involves using a more specific selector to ensure the `:hover` effect is only applied when the outer `div` is directly hovered over, not its descendants.  The solution file shows how to correctly target the outer `div` using appropriate selectors.