SELECT
  member_casual,
  day_of_week,
  COUNT(*) AS total_rides,
  AVG(ride_length_minutes) AS avg_ride_length
FROM `project-e48f5d78-a5e7-45de-a67.divvy_analysis.all_trips_clean`
GROUP BY member_casual, day_of_week
ORDER BY day_of_week, member_casual;
