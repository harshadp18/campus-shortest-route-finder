# Campus Shortest Route Finder

## PBLE 2 – Dijkstra's Algorithm

A menu-driven C program that finds the shortest route between campus locations using Dijkstra's Algorithm.

## Problem Statement

A college campus consists of several locations connected by roads. Each road has a distance. The program represents the campus as a weighted graph and finds the shortest distance from a selected source location to every other location.

## Locations

- Main Gate
- Library
- Computer Department
- Laboratory
- Auditorium

## Algorithm Used

Dijkstra's Algorithm

## Data Structure

Adjacency Matrix

## Features

1. Enter Campus Graph
2. Display Adjacency Matrix
3. Select Source Location
4. Find Shortest Distance
5. Display Shortest Paths
6. Display Distance from Source
7. Exit

## Example Result

Source: Main Gate

| Destination | Distance | Shortest Path |
|---|---:|---|
| Main Gate | 0 | Main Gate |
| Library | 4 | Main Gate → Library |
| Computer Department | 7 | Main Gate → Library → Computer Department |
| Laboratory | 9 | Main Gate → Library → Computer Department → Laboratory |
| Auditorium | 14 | Main Gate → Library → Computer Department → Laboratory → Auditorium |

## Complexity

Time Complexity: O(V²)

Space Complexity: O(V²)

## Language

C

## Subject

Analysis of Algorithms (AOA)

## PBLE

PBLE 2 – Campus Shortest Route Finder
