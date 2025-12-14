---
layout: default
title: Projects
description: Open source projects for Sinhala language technology
---

<section class="page-header">
    <div class="container">
        <h1>Our Projects</h1>
        <p>Open source tools and libraries for Sinhala language technology</p>
    </div>
</section>

<section class="projects">
    <div class="container">
        <div class="project-card">
            <div class="project-header">
                <h2>sinhala-text-converters</h2>
                <div class="project-badges">
                    <span class="badge badge-npm">npm</span>
                    <span class="badge badge-typescript">TypeScript</span>
                </div>
            </div>
            <p class="project-description">
                A TypeScript/JavaScript library for converting between Singlish (Sinhala written in English) 
                and Unicode Sinhala formats. This package makes it easy to work with Sinhala text in different 
                formats within your applications.
            </p>
            
            <div class="project-features">
                <h3>Features</h3>
                <ul>
                    <li>Convert Singlish to Unicode Sinhala</li>
                    <li>Convert Unicode Sinhala to Singlish</li>
                    <li>TypeScript support with full type definitions</li>
                    <li>Flexible conversion options and error handling</li>
                    <li>Well-tested and production-ready</li>
                </ul>
            </div>

            <div class="project-links">
                <h3>Links</h3>
                <div class="link-buttons">
                    <a href="https://github.com/sinhala-soft/sinhala-text-converters" target="_blank" rel="noopener noreferrer" class="btn btn-github">
                        <svg width="16" height="16" viewBox="0 0 16 16" fill="currentColor">
                            <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.012 8.012 0 0 0 16 8c0-4.42-3.58-8-8-8z"/>
                        </svg>
                        View on GitHub
                    </a>
                    <a href="https://www.npmjs.com/package/sinhala-text-converters" target="_blank" rel="noopener noreferrer" class="btn btn-npm">
                        <svg width="16" height="16" viewBox="0 0 18 7" fill="currentColor">
                            <path d="M0 0h18v6H9v1H5V6H0V0zm1 5h2V2h1v3h1V1H1v4zm5-4v5h2V5h2V1H6zm2 1h1v2H8V2zm3-1v4h2V2h1v3h1V2h1v3h1V1h-6z"/>
                        </svg>
                        View on npm
                    </a>
                </div>
            </div>

            <div class="project-install">
                <h3>Installation</h3>
                <div class="code-block">
                    <code>npm install sinhala-text-converters</code>
                </div>
            </div>

            <div class="project-usage">
                <h3>Quick Example</h3>
                <div class="code-block">
                    <pre><code>import { singlishToUnicode, unicodeToSinglish } from 'sinhala-text-converters';

// Convert Singlish to Unicode
const unicode = singlishToUnicode('aayubowan');
console.log(unicode); // Output: ආයුබෝවන්

// Convert Unicode to Singlish
const singlish = unicodeToSinglish('ආයුබෝවන්');
console.log(singlish); // Output: aayubowan</code></pre>
                </div>
            </div>

            <div class="project-credits">
                <h3>Credits</h3>
                <p>
                    All conversion algorithms originated from the <strong>Language Technology Research Laboratory</strong> 
                    at the University of Colombo School of Computing (UCSC). This package is maintained by 
                    Sinhala Soft Foundation.
                </p>
                <p>
                    <a href="https://ucsc.cmb.ac.lk/ltrl/services/feconverter" target="_blank" rel="noopener noreferrer">
                        Original UCSC Converter Service
                    </a>
                </p>
            </div>
        </div>
    </div>
</section>

