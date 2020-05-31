Application Architecture:

Root dir = `/vane_exchange_live
sub directories = `/assets, `/images
nested directories = `/node_modules, `/css, `/js, `/sass, `/webfonts, `/fulls, `/thumbs, `/bundles
Server = Express
Public IP's:
Dependencies: node-media-server, underscore.js, wintersmith, base.js, bottleneck, n8n
Author: HJP

Flows;

GCP, AWS, LIN, MAZ etc link through to integrated quote + explanation calculators, which pass on to payment system backends and Authentication. SoloLearn, or other certifications that need to be verified can be 