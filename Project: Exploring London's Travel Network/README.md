Write three SQL queries to answer the following questions:

<ol>
  <li>
    <h3> What are the most popular transport types, measured by the total number of journeys? </h3>
    The output should contain two columns: <code>JOURNEY_TYPE</code> and <code>TOTAL_JOURNEYS_MILLIONS</code>, and be sorted by the second column in descending order. Save the query as <code>most_popular_transport_types</code>
  </li>
  <li>
    <h3> Which 5 months and years were the most popular for the Emirates Airline? </h3>
    Return an output containing <code>MONTH</code>, <code>YEAR</code>, and <code>JOURNEYS_MILLIONS</code>, with the latter rounded to two decimal places and aliased as <code>ROUNDED_JOURNEYS_MILLIONS</code>. Exclude null values and save the result as <code>emirates_airline_popularity</code>
  </li>
  <li>
    <h3> Find the 5 years with the lowest volume of <code>Underground & DLR</code> journeys </h3>
    Save this as <code>least_popular_years_tube</code>. The results should contain the columns <code>YEAR</code>, <code>JOURNEY_TYPE</code>, <code>TOTAL_JOURNEYS_MILLIONS</code>
  </li>
</ol>

Three SQL cells have been created for you in the workbook. To access the Snowflake database, you will need to select data using the syntax <code>FROM TFL.JOURNEYS</code> (ensure you use upper-case).
