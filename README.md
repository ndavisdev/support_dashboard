# Support Operations Dashboard

A browser-based support operations dashboard built with HTML, CSS, JavaScript, and Supabase. The app lets users create, update, organize, lock, delete, sync, and export support cases from a persistent backend.

## Live Demo

Add your hosted link here.

## GitHub Repository

Add your GitHub repo link here.

## Why I Built This

I built this project to demonstrate frontend development, backend integration, and workflow-focused product thinking. The goal was to create a lightweight internal tool similar to what a support, operations, or technical project team could use to track active issues, ownership, SLA risk, and case status.

This project connects directly to a Supabase backend, so case data persists beyond the browser session.

## Features

* Create, edit, delete, and lock support cases
* Persistent Supabase backend storage
* Sync Data button to pull latest backend records
* Kanban view with drag-and-drop status updates
* Table view with filtering and sorting
* Case status overview chart
* SLA risk tracking
* CSV export
* Light and dark mode
* Custom delete confirmation modal
* Controlled issue type dropdowns for cleaner demo data

## Tech Stack

* HTML
* CSS
* JavaScript
* Supabase
* REST API
* Local browser UI state
* Responsive layout

## What This Demonstrates

* Frontend UI development
* DOM manipulation
* API integration
* CRUD workflows
* Persistent data handling
* Form validation and controlled inputs
* UX decisions for destructive actions
* State-driven rendering
* Kanban-style workflow design

## How to Test

1. Open the live demo.
2. Click **Sync Data** to pull records from Supabase.
3. Create a new case using the form.
4. Refresh the page and click **Sync Data** to confirm persistence.
5. Switch to **Kanban View**.
6. Drag an unlocked case between columns.
7. Lock a case and confirm it can no longer be moved or deleted.
8. Export the visible data as CSV.

## Notes

This is a demo application connected to a Supabase project. In production, this would use authentication, row-level security policies, and role-based permissions.
