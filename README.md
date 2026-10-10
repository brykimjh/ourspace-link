# OurSpace connection

Permanent bookmark: https://brykimjh.github.io/ourspace-link/

This public repository holds only a redirect page and the current public tunnel address. It contains no planner data, application source, credentials, or passcode. The private laptop launcher updates target.json automatically on startup and marks it offline on normal shutdown.

The laptop must be running and connected to the internet. If it stops abruptly, the pointer may still lead to an expired tunnel. Return to the bookmark after the laptop restarts. The sign-in passcode is entered on the app, never supplied through this repository or its URL.

The page reads target.json through GitHub's public Contents API to avoid waiting for a Pages rebuild on every connection update. It falls back to raw content if the API is unavailable or rate limited. Anonymous GitHub API requests have a limit of 60 per hour per IP; one page opening makes one request. The fallback can briefly show an older cached destination.
