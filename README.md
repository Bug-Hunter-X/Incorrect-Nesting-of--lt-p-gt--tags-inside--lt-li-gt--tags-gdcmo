# Incorrect Nesting of &lt;p&gt; tags inside &lt;li&gt; tags

This repository demonstrates a common HTML error: incorrectly nesting &lt;p&gt; (paragraph) tags within &lt;li&gt; (list item) tags. This can lead to unexpected behavior and accessibility issues. The `bug.html` file shows the incorrect nesting, while `bugSolution.html` provides the corrected version.

**Problem:**
Paragraph elements (&lt;p&gt;) should not be nested directly inside list items (&lt;li&gt;).  While browsers might render it, it's semantically incorrect and can cause unexpected layout or accessibility problems.

**Solution:**
The content within the &lt;p&gt; tags should be placed directly within the &lt;li&gt; tag without the additional paragraph nesting.  This ensures the correct semantic structure and improves accessibility.
