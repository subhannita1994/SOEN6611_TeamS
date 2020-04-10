# SOEN6611_TeamS
SOEN6611 Software Measurement Winter 2020 Term Project : Performance Metrics and Correlation Analysis on several Open Source Projects.



## Selected Metrics
Statement coverage, Branch coverage, Mutation score of test suite, McCabe Cyclomatic Complexity, Code churn and Defect Density.

## Selected Open source projects
<ol>
  <li><a href = https://github.com/apache/commons-collections>Apache Commons Collection</a></li>
  <li><a href = https://github.com/apache/commons-io>Apache Commons IO</a></li>
  <li><a href = https://gitbox.apache.org/repos/asf?p=commons-fileupload.git;a=tags>Apache Commons FileUpload</a></li>
  </ol>
 
### Project structure of each project 
<dl>
  <dt>Configuration file for each version</dt>
  <dd>Contains pom.xml</dd>
  <dt>Jacoco reports<dt>
  <dd>Contains statement coverave, branch coverage, McCable Complexity, number of missed lines, number of missed methods, number of missed classes</dd>
  <dt>PIT report</dt>
  <dd>Contains Line coverage and Mutation score</dd>
  <dt>Defect Density</dt>
  <dd>Contains number of defects, SLOC and corresponding defect density for each version</dd>
  <dt>Code churn</dt>
  <dd>The number of lines of code added, deleted and modified through several versions</dd>
  <dt>Correlation analysis</dt>
  <dd>
    <dl>
      <dd>1. Correlation analysis between statement coverage and mutation score</dd>
      <dd>2. Correlation analysis between branch coverage and mutation score</dd>
      <dd>3. Correlation analysis between statement coverage and complexity score</dd>
      <dd>4. Correlation analysis between branch coverage and complexity score</dd>
      <dd>5. Correlation analysis between statement coverage and defect density</dd>
      <dd>6. Correlation analysis between branch coverage and defect density</dd>
      <dd>7. Correlation analysis between code churn and defect density</dd>
    </dl>
  </dd>
  </dl>

### Requirements
<ul>
  <li>Install Maven following these <a href = "http://maven.apache.org/install.html">instructions</a></li>
  <li>Download the source code for the corresponding versions of each project from their SCM - 
    <ul>
      <li>Apache commons collections - </li>
      <li>Apache commons FileUpload - </li>
      <li>Apache commons IO - </li>
    </ul>
  </li>
  <li>Replace the pom.xml files with the ones provided for each version. Make sure to change the JUnit plugin versions to at least 4.6 for compatibility with PIT tool</li>
  <li>Clean and install the project</li>
  <li>Run the project with goal - org.pitest:pitest-maven:mutationCoverage</li>
  <li>Check for jacoco and pit reports in the target folder</li>
</ul>

## Team information
<table>
  <caption>Team S</caption>
  <tr>
    <th>Name</th>
    <th>email address</th>
    <th>Student ID</th>
  </tr>
  <tr>
    <td>Subhannita Sarcar</td>
    <td>subhannitasarcar1994@gmail.com</td>
    <td>40059367</td>
  </tr>
  <tr>
    <td>Gurwinder Kaur</td>
    <td>kaurgurwinder2013@gmail.com</td>
    <td>40080390</td>
  </tr>
  <tr>
    <td>Jasmine Kaur</td>
    <td>jasmine14concordia@gmail.com</td>
    <td>40103309</td>
  </tr>
  <tr>
    <td>Raghav Verma</td>
    <td>raghav.1995@yahoo.com</td>
    <td>40076250</td>
  </tr>
  </table>
