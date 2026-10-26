---
name: travel-planner
description: Plan practical, destination-specific trips with sightseeing, food stops, realistic routing, and weather alternatives. Use when creating or adapting travel itineraries; not for booking travel.
metadata:
  short-description: Plan trips and itineraries
---

# Travel Planner

Create a useful itinerary for the destination, dates, and preferences the user gives. The skill is destination-agnostic: never assume Tokyo or any other place from a past example. If key details are missing, make sensible assumptions and state them; ask only when the missing detail would materially change the route or feasibility.

## Build the itinerary

- Check current, changeable details when relevant: opening days and hours, closures, seasonal events, transit disruption, weather, and reservation requirements. Prefer official venue or transit sources for operating details. Cite direct links near claims when browsing.
- Arrange activities into geographic clusters and minimize backtracking. Account for arrival/departure times, hotel location if known, meal times, realistic visit durations, and transfer time. Avoid overloading each day.
- Include food options near the sights, matching stated preferences and budget when supplied. Explain when a market or restaurant district has limited hours or closures. Do not invent confirmed reservations or guaranteed availability.
- Present a clear day-by-day schedule with approximate times, transport notes where useful, and concise practical tips. Label assumptions and distinguish verified facts from suggestions.
- If the user asks for overnight travel, cover each day and note where the overnight stay best fits the route when lodging location is unknown.

## Weather and contingencies

When requested, provide a separate bad-weather version or identify indoor substitutions alongside the affected outdoor stops. Keep alternatives geographically close to the original route, check their operating days, and include a reasonable fallback if a venue is closed. Do not claim a forecast far in advance; use forecast information only when it is meaningful for the travel date.

## References and links

When asked for blogs, local guides, or other references, find real, relevant pages and provide direct links. Identify the source type and, where available, its publication date. Do not pad the list with generic search links or unrelated examples. Make clear that user-generated posts may contain outdated hours, prices, or availability; verify operational details separately.

## Scope

Planning does not authorize purchases, reservations, messages, or other external commitments. Provide booking links or instructions when useful, and act on bookings only if the user explicitly asks and the available workflow supports it.
