# c--notes
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Premium C Programming Notes</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="page-shell">
        <header class="topbar">
            <div class="brand">GAGANDEEP<span> C CODE</span></div>
            <nav class="nav">
                <a href="index.html">Home</a>
                <a href="variables.html">Variables</a>
                <a href="#examples">Examples</a>
            </nav>
        </header>

        <main class="hero">
            <div class="hero-text">
                <p class="eyebrow">Learn. Build. Master.</p>
                <h1>Premium C Programming Notes</h1>
                <p class="subtitle">
                    Explore clean, practical examples and sharpen your coding skills with a modern learning experience.
                </p>
                <div class="cta-row">
                    <a href="#examples" class="btn primary">View Examples</a>
                    <a href="variables.html" class="btn secondary">Explore Topics</a>
                </div>
            </div>

            <div class="code-card">
                <div class="card-header">
                    <span class="dot red"></span>
                    <span class="dot yellow"></span>
                    <span class="dot green"></span>
                    <h3>Traffic Signal</h3>
                </div>
            </div>
        </main>

        <section class="features" id="examples">
            <article class="feature-card">
                <span class="tag">01</span>
                <h2>Hello World</h2>
                <p>The classic starting point for every C programmer.</p>
                <pre><code>#include &lt;stdio.h&gt;

int main() {
    printf("Hello, World!\\n");
    return 0;
}</code></pre>
            </article>

            <article class="feature-card spotlight">
                <span class="tag">02</span>
                <h2>Sum of Two Numbers</h2>
                <p>A simple program that reads two integers and prints their sum.</p>
                <pre><code>#include &lt;stdio.h&gt;
#include &lt;conio.h&gt;

void main() {
    int a, b, sum;

    printf("Enter two numbers: ");
    scanf("%d %d", &amp;a, &amp;b);

    sum = a + b;
    printf("Sum = %d\\n", sum);

    return 0;
}</code></pre>
            </article>

            <article class="feature-card">
                <span class="tag">03</span>
                <h2>Area of a Triangle</h2>
                <p>Find the area using the base and height. This integer version follows the original <code>conio.h</code> style.</p>
                <pre><code>#include &lt;stdio.h&gt;
#include &lt;conio.h&gt;
void main()
{
    int l, b, Area;

    printf("Enter two values for finding the area of a triangle: ");
    scanf("%d%d", &l,&b);


    Area = (l * b) / 2;
    printf("Area of triangle is %d", Area);

    getch();
    return 0;
}</code></pre>
            </article>
        </section>
    </div>
</body>
</html>
