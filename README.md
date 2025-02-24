# Inconsistent Text Color with Similar Gray Shades in Tailwind CSS

This repository demonstrates a common issue when using Tailwind CSS: text becoming unreadable due to similar shades of gray used for background and text colors.  The problem arises from a lack of sufficient contrast between the text and background colors, resulting in poor readability.  A solution is provided to improve contrast using more distinct color choices or Tailwind's contrast utility classes.

## Bug Report

The provided code snippet showcases the problem. The dark gray text ("text-gray-800") on the light gray background ("bg-gray-100") creates a low-contrast scenario that makes the text difficult to read.

## Solution

The solution involves changing to a higher contrast combination; this can be done in several ways:

1. Switching to darker background:
2. Switching to lighter text color:
3. Using Tailwind's contrast utility classes to ensure sufficient contrast ratio.

The solution file illustrates the implementation of these approaches.