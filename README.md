<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Steveb A. Miller, Ph.D.</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
        }
        
        h1, h2, h3, h4 {
            font-family: 'Helvetica', 'Arial', sans-serif;
            color: #14213d;
        }
        
        h1 {
            text-align: center;
            margin-bottom: 5px;
            font-size: 32px;
        }
        
        .contact-info {
            text-align: center;
            margin-bottom: 40px;
            font-style: normal;
            font-size: 16px;
        }
        
        .contact-info a {
            color: #457b9d;
            text-decoration: none;
        }
        
        .contact-info a:hover {
            text-decoration: underline;
        }
        
        .section {
            margin-bottom: 30px;
        }
        
        h2 {
            border-bottom: 2px solid #14213d;
            padding-bottom: 5px;
            margin-top: 30px;
        }
        
        h3 {
            margin-bottom: 5px;
            font-size: 18px;
        }
        
        .entry {
            margin-bottom: 20px;
        }
        
        .entry-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 5px;
        }
        
        .position {
            font-weight: bold;
        }
        
        .date {
            font-style: italic;
        }
        
        .institution {
            font-style: italic;
        }
        
        ul {
            padding-left: 20px;
        }
        
        li {
            margin-bottom: 5px;
        }
        
        .print-button {
            position: fixed;
            top: 20px;
            right: 20px;
            padding: 8px 16px;
            background-color: #14213d;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        
        @media print {
            .print-button {
                display: none;
            }
            
            body {
                padding: 0;
                font-size: 12px;
            }
            
            h1 {
                font-size: 24px;
            }
            
            h2 {
                font-size: 18px;
            }
            
            h3 {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>
    <button class="print-button" onclick="window.print()">Print CV</button>
    
    <h1>Steven A. Miller, Ph.D.</h1>
    <div class="contact-info">
        <p>
            Department, University • City, State/Country<br>
            <a href="mailto:steven.miller@rosalindfranklin.edu">steven.miller@rosalindfranklin.edu</a> • 
            <a href="https://yourusername.github.io">yourusername.github.io</a> • 
            <a href="https://orcid.org/0000-0001-6687-776X">ORCID</a> • 
            <a href="https://scholar.google.com/citations?user=ggne6LkAAAAJ&hl=en">Google Scholar</a>
        </p>
    </div>
    
    <div class="section">
        <h2>Education</h2>
        
        <div class="entry">
            <div class="entry-header">
                <span class="position">Ph.D. in Your Field</span>
                <span class="date">Year - Year</span>
            </div>
            <div class="institution">University Name, Location</div>
            <p>Dissertation: "Title of Your Dissertation"</p>
            <p>Advisor: Professor Name</p>
        </div>
        
        <div class="entry">
            <div class="entry-header">
                <span class="position">M.S./M.A. in Your Field</span>
                <span class="date">Year - Year</span>
            </div>
            <div class="institution">University Name, Location</div>
            <p>Thesis: "Title of Your Thesis" (if applicable)</p>
        </div>
        
        <div class="entry">
            <div class="entry-header">
                <span class="position">B.S./B.A. in Your Field</span>
                <span class="date">Year - Year</span>
            </div>
            <div class="institution">University Name, Location</div>
        </div>
    </div>
    
    <div class="section">
        <h2>Academic Positions</h2>
        
        <div class="entry">
            <div class="entry-header">
                <span class="position">Assistant/Associate/Full Professor</span>
                <span class="date">Year - Present</span>
            </div>
            <div class="institution">Department, University, Location</div>
            <ul>
                <li>Brief description of responsibilities and achievements</li>
                <li>Another responsibility or achievement</li>
            </ul>
        </div>
        
        <div class="entry">
            <div class="entry-header">
                <span class="position">Postdoctoral Researcher</span>
                <span class="date">Year - Year</span>
            </div>
            <div class="institution">Research Group/Lab, University, Location</div>
            <ul>
                <li>Brief description of research focus</li>
                <li>Key accomplishments</li>
            </ul>
        </div>
    </div>
    
    <div class="section">
        <h2>Publications</h2>
        
        <h3>Peer-Reviewed Journal Articles</h3>
        <ul>
            <li>Author, A., Author, B., & <strong>Your Name</strong>. (Year). Title of the paper. <em>Journal Name</em>, Volume(Issue), pages. DOI: <a href="#">link</a></li>
            <li>Author, A., <strong>Your Name</strong>, & Author, C. (Year). Title of the paper. <em>Journal Name</em>, Volume(Issue), pages. DOI: <a href="#">link</a></li>
            <li>Add more publications as needed...</li>
        </ul>
        
        <h3>Conference Proceedings</h3>
        <ul>
            <li><strong>Your Name</strong>, Author, A. (Year). Title of the paper. In <em>Proceedings of Conference Name</em>, Location, pages. DOI: <a href="#">link</a></li>
            <li>Add more conference papers as needed...</li>
        </ul>
        
        <h3>Book Chapters</h3>
        <ul>
            <li>Author, A., <strong>Your Name</strong>, & Author, B. (Year). Title of the chapter. In Editor(s) (Ed.), <em>Book Title</em> (pp. pages). Publisher.</li>
            <li>Add more book chapters as needed...</li>
        </ul>
    </div>
    
    <div class="section">
        <h2>Research</h2>
        
        <h3>Grants & Funding</h3>
        <ul>
            <li>"Grant Title" (Role: PI/Co-PI), Funding Agency, $Amount, Year-Year</li>
            <li>Add more grants as needed...</li>
        </ul>
        
        <h3>Research Projects</h3>
        <ul>
            <li>Title of Research Project, Brief description of the project and your role. Year-Year</li>
            <li>Add more research projects as needed...</li>
        </ul>
    </div>
    
    <div class="section">
        <h2>Teaching Experience</h2>
        
        <div class="entry">
            <div class="entry-header">
                <span class="position">Course Name (Course Number)</span>
                <span class="date">Semester, Year</span>
            </div>
            <div class="institution">University Name</div>
            <p>Brief description of your role and responsibilities for this course.</p>
        </div>
        
        <div class="entry">
            <div class="entry-header">
                <span class="position">Another Course (Course Number)</span>
                <span class="date">Semester, Year</span>
            </div>
            <div class="institution">University Name</div>
            <p>Brief description of your role and responsibilities for this course.</p>
        </div>
    </div>
    
    <div class="section">
        <h2>Presentations</h2>
        
        <h3>Invited Talks</h3>
        <ul>
            <li>"Title of Talk," Conference/Event Name, Location, Month Year</li>
            <li>Add more talks as needed...</li>
        </ul>
        
        <h3>Conference Presentations</h3>
        <ul>
            <li>"Title of Presentation," Conference Name, Location, Month Year</li>
            <li>Add more presentations as needed...</li>
        </ul>
    </div>
    
    <div class="section">
        <h2>Service & Leadership</h2>
        
        <h3>Professional Service</h3>
        <ul>
            <li>Reviewer for Journal Name, Year-Present</li>
            <li>Committee Member, Organization/Conference Name, Year-Year</li>
            <li>Add more service roles as needed...</li>
        </ul>
        
        <h3>University Service</h3>
        <ul>
            <li>Committee Member, Committee Name, Department/University, Year-Year</li>
            <li>Faculty Advisor, Student Group Name, Year-Year</li>
            <li>Add more university service roles as needed...</li>
        </ul>
    </div>
    
    <div class="section">
        <h2>Skills</h2>
        
        <h3>Technical Skills</h3>
        <ul>
            <li>Programming Languages: List languages</li>
            <li>Software: List software</li>
            <li>Research Methods: List methods</li>
            <li>Add more technical skills as needed...</li>
        </ul>
        
        <h3>Languages</h3>
        <ul>
            <li>Language 1 (Native/Fluent/Advanced/Intermediate/Basic)</li>
            <li>Language 2 (Native/Fluent/Advanced/Intermediate/Basic)</li>
            <li>Add more languages as needed...</li>
        </ul>
    </div>
    
    <div class="section">
        <h2>Honors & Awards</h2>
        <ul>
            <li>Award Name, Awarding Institution/Organization, Year</li>
            <li>Fellowship Name, Awarding Institution, Year-Year</li>
            <li>Add more honors and awards as needed...</li>
        </ul>
    </div>
    
    <div class="section">
        <h2>Professional Memberships</h2>
        <ul>
            <li>Name of Professional Organization, Year-Present</li>
            <li>Name of Another Professional Organization, Year-Present</li>
            <li>Add more memberships as needed...</li>
        </ul>
    </div>
    
    <div class="section">
        <h2>References</h2>
        <p>Available upon request.</p>
        <!-- Alternatively, you can list your references here -->
        <!--
        <div class="entry">
            <div class="position">Professor Full Name</div>
            <div class="institution">Title, Department, University</div>
            <p>Email: email@university.edu</p>
            <p>Phone: (123) 456-7890</p>
        </div>
        -->
    </div>
    
    <script>
        // You can add any JavaScript here if needed
        // For example, to automatically update the year in the footer
    </script>
</body>
</html>
