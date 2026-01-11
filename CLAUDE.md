# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple MCP (Model Context Protocol) app project containing standalone web applications. Currently includes a shopping list app built with vanilla HTML/CSS/JavaScript.

## Architecture

- **Standalone HTML files**: Each app is a self-contained single HTML file with embedded CSS and JavaScript
- **No build system**: Files run directly in the browser without compilation
- **localStorage persistence**: Client-side data storage using browser localStorage

## Running Applications

Open HTML files directly in a browser (double-click or use file:// protocol).

## Code Conventions

- Korean language UI (한국어 인터페이스)
- Single-file architecture with inline `<style>` and `<script>` tags
- Use `escapeHtml()` pattern for XSS prevention when rendering user input
