# Blogging with N8N

A comprehensive AI-powered blogging automation system built with N8N that creates, optimizes, and publishes high-quality blog content automatically.

## Project Objective

This project demonstrates a complete automated blogging workflow that transforms a simple topic request into a fully published, SEO-optimized blog post. The system uses multiple specialized AI agents working in sequence to handle every aspect of content creation, from initial research to final publication on your Ghost CMS website.

## How It Works

The workflow orchestrates a team of AI agents, each specializing in a specific aspect of content creation. Starting with a user's topic request, the system automatically:
1. **Researches** the topic comprehensively
2. **Creates** a structured table of contents
3. **Generates** engaging, well-researched content
4. **Optimizes** for SEO and search visibility
5. **Edits** and polishes the content
6. **Publishes** directly to your Ghost CMS website

## Agent Roles & Responsibilities

### 🤖 Blog Content Orchestrator Agent
**The Project Manager** - Coordinates the entire workflow, manages data flow between agents, and ensures quality control at each stage. This agent handles user interactions, validates data, and manages approval gates before proceeding to publication.

### 🔍 Research Agent
**The Information Specialist** - Conducts comprehensive research using multiple sources including Brave Search, Brave News, and your existing blog content. Creates compelling table of contents, identifies content gaps, and provides research insights for content generation.

### ✍️ Content Generator Agent
**The Master Writer** - Transforms research insights and approved TOC into engaging, well-cited blog content. Researches each section individually, includes proper citations, and maintains consistent style throughout the article.

### 🎯 SEO Optimizer Agent
**The Search Expert** - Performs comprehensive SEO optimization including keyword research, on-page optimization, meta tag generation, and content enhancement recommendations. Ensures maximum search visibility and ranking potential.

### ✂️ Content Editor Agent
**The Quality Assurance Specialist** - Enhances content readability, verifies citations, improves flow, and ensures all links are functional. Creates professional HTML-formatted content ready for publication.

### 🚀 Blog HTML Publisher Agent
**The Publication Specialist** - Generates complete HTML documents with SEO meta tags, schema markup, and social media optimization. Automatically publishes content to your Ghost CMS website using the Ghost Publisher Tool.

## Key Features

- **Fully Automated**: From topic to published post with minimal human intervention
- **AI-Powered**: Multiple specialized AI agents working in sequence
- **SEO Optimized**: Comprehensive search engine optimization at every stage
- **Ghost CMS Integration**: Direct publishing to your website
- **Quality Control**: Multiple approval gates and validation steps
- **Research-Driven**: Comprehensive research using multiple sources
- **Citation Management**: Proper source attribution and internal linking
- **Content Consistency**: Maintains brand voice and style throughout

## Workflow Benefits

- **Time Savings**: Reduce content creation time from hours to minutes
- **Quality Consistency**: Maintain high standards across all content
- **SEO Performance**: Built-in optimization for better search rankings
- **Scalability**: Create multiple high-quality posts efficiently
- **Research Depth**: Comprehensive research using multiple sources
- **Professional Output**: Publication-ready content with proper formatting

## Getting Started

1. **Install N8N** on your system
2. **Import the workflow** from the JSON file
3. **Configure API credentials** for OpenAI, Anthropic, Brave Search, and Ghost CMS
4. **Set up your agents** with the provided system messages
5. **Start the workflow** by requesting a blog topic

## Requirements

- N8N instance
- OpenAI API key (for GPT models)
- Anthropic API key (for Claude models)
- Brave Search API key
- Ghost CMS admin API access
- Existing blog content for reference (optional but recommended)



## Workflow Structure

The system follows a 7-phase workflow:
1. **Topic Planning** - User input and requirements gathering
2. **Research & TOC** - Comprehensive research and outline creation
3. **Content Generation** - AI-powered content creation
4. **SEO Optimization** - Search engine optimization
5. **Content Editing** - Quality enhancement and polishing
6. **User Review** - Final approval before publication
7. **Publication** - Automatic posting to Ghost CMS

## License

MIT License - Feel free to use, modify, and distribute this project.

## Contributing

This project demonstrates advanced N8N workflow automation and AI agent orchestration. Contributions and improvements are welcome!
