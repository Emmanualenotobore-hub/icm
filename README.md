<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sample Paper — Springer LNCS Style (HTML Version)</title>
  <style>
    body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 40px; background-color: #f9fafc; color: #111; }
    header { text-align: center; margin-bottom: 40px; }
    h1 { font-size: 1.8em; }
    h2, h3, h4 { color: #1e40af; }
    table { border-collapse: collapse; width: 100%; margin: 16px 0; }
    table, th, td { border: 1px solid #ccc; }
    th, td { padding: 8px 12px; text-align: left; }
    figure { margin: 20px 0; text-align: center; }
    figcaption { font-size: 0.9em; color: #444; }
    code, pre { background: #0f172a; color: #e2e8f0; padding: 8px; border-radius: 4px; display: block; overflow-x: auto; }
    footer { margin-top: 40px; font-size: 0.9em; color: #666; text-align: center; }
  </style>
</head>
<body>
  <header>
    <h1>Contribution Title</h1>
    <p><em>Supported by organization x.</em></p>
  </header>

  <section id="authors">
    <h2>Authors</h2>
    <p><strong>First Author</strong> (Princeton University, USA) — ORCID: 0000-1111-2222-3333</p>
    <p><strong>Second Author</strong> (Springer Heidelberg, Germany) — ORCID: 1111-2222-3333-4444</p>
    <p><strong>Third Author</strong> (ABC Institute, Heidelberg, Germany) — ORCID: 2222-3333-4444-5555</p>
  </section>
  <section id="abstract">
    <h2>Abstract</h2>
    <p>The abstract should briefly summarize the contents of the paper in 150–250 words.</p>
    <p><strong>Keywords:</strong> First keyword, Second keyword, Another keyword.</p>
  </section>
  <section id="introduction">
    <h2>1. First Section</h2>
    <h3>1.1 A Subsection Sample</h3>
    <p>The first paragraph of a section or subsection is not indented. The first paragraph that follows a table, figure, or equation does not need an indent either.</p>
    <p>Subsequent paragraphs, however, are indented.</p>
    <h4>Sample Heading (Third Level)</h4>
    <p>Only two levels of headings should be numbered. Lower-level headings remain unnumbered and are formatted as run-in headings.</p>
    <h4>Sample Heading (Fourth Level)</h4>
    <p>The contribution should contain no more than four levels of headings.</p>
    <table>
      <caption>Table captions should be placed above the tables.</caption>
      <thead>
        <tr><th>Heading level</th><th>Example</th><th>Font size and style</th></tr>
      </thead>
      <tbody>
        <tr><td>Title (centered)</td><td><strong>Lecture Notes</strong></td><td>14 point, bold</td></tr>
        <tr><td>1st-level heading</td><td><strong>1 Introduction</strong></td><td>12 point, bold</td></tr>
        <tr><td>2nd-level heading</td><td><strong>2.1 Printing Area</strong></td><td>10 point, bold</td></tr>
        <tr><td>3rd-level heading</td><td><strong>Run-in Heading in Bold.</strong> Text follows</td><td>10 point, bold</td></tr>
        <tr><td>4th-level heading</td><td><em>Lowest Level Heading.</em> Text follows</td><td>10 point, italic</td></tr>
      </tbody>
    </table>
    <h3>Displayed Equation</h3>
    <pre>x + y = z</pre>
    <figure>
      <img src="fig1.png" alt="Sample figure" width="80%" />
      <figcaption>A figure caption is always placed below the illustration. Short captions are centered; long ones are justified.</figcaption>
    </figure>
  </section>
  <section id="theorem">
    <h2>Theorem Example</h2>
    <p><strong>Theorem:</strong> This is a sample theorem. The run-in heading is set in bold, while the following text appears in italics. Definitions, lemmas, propositions, and corollaries are styled the same way.</p>
    <p><strong>Proof:</strong> Proofs, examples, and remarks have the initial word in italics, while the following text appears in normal font.</p>
  </section>
  <section id="references">
    <h2>References</h2>
    <ol>
      <li>Author, F.: Article title. <em>Journal</em> <strong>2</strong>(5), 99–110 (2016)</li>
      <li>Author, F., Author, S.: Title of a proceedings paper. In: Editor, F., Editor, S. (eds.) <em>CONFERENCE 2016</em>, LNCS, vol. 9999, pp. 1–13. Springer, Heidelberg (2016). DOI: 10.10007/1234567890</li>
      <li>Author, F., Author, S., Author, T.: Book title. 2nd edn. Publisher, Location (1999)</li>
      <li>Author, A.-B.: Contribution title. In: 9th International Proceedings on Proceedings, pp. 1–2. Publisher, Location (2010)</li>
      <li>LNCS Homepage: <a href="http://www.springer.com/lncs">http://www.springer.com/lncs</a>. Last accessed 4 Oct 2017</li>
    </ol>
  </section>

  <footer>
    <p>Converted from Springer LNCS LaTeX template (samplepaper.tex) to HTML for web-based representation.</p>
  </footer>
</body>
</html>
