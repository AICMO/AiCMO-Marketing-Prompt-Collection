# HubSpot Integration Guide - Complete Marketing Automation

**Setup Time:** 30 minutes | **Difficulty:** Intermediate | **Impact:** High

Transform your HubSpot instance into an AI-powered marketing machine using AICMO prompts.

## 🎯 What You'll Achieve

- **Automated Lead Scoring** based on AI-generated ICP criteria
- **Personalized Email Sequences** created with AI prompts
- **Dynamic Content** that adapts to visitor behavior
- **Automated Social Posts** from blog content
- **Smart Contact Segmentation** using AI insights

## 📋 Prerequisites

✅ HubSpot Marketing Hub (Starter, Professional, or Enterprise)  
✅ ChatGPT Plus or Claude Pro subscription  
✅ Admin access to your HubSpot account  
✅ Basic familiarity with HubSpot workflows  

## 🚀 Quick Setup (15 minutes)

### **Step 1: Generate Your ICP Criteria (5 minutes)**

1. Use the [ICP Identification Prompt](../02_Product-Marketing/Customer-&-Market-Research/ICP-Identification.md)
2. Generate your top 3 ICPs with specific criteria
3. Note the key characteristics for each ICP

**Example Output Format for HubSpot:**
```
ICP 1: Tech Startups
- Company Size: 25-100 employees  
- Industry: Software/Technology
- Job Title: VP Marketing, CMO, Head of Growth
- Annual Revenue: $2M-$20M
- Tech Stack: Uses Slack, Zoom, modern SaaS tools
```

### **Step 2: Create HubSpot Properties (5 minutes)**

In HubSpot, create custom contact properties:
1. Go to **Settings > Properties > Contact Properties**
2. Create new properties:
   - `ICP_Score` (Number, 1-10 scale)
   - `ICP_Category` (Dropdown: ICP1, ICP2, ICP3, Not_Qualified)
   - `AI_Generated_Tags` (Multiple checkboxes)
   - `Pain_Points` (Multi-line text)

### **Step 3: Setup Lead Scoring (5 minutes)**

1. Go to **Settings > Lead Scoring**
2. Create scoring criteria based on your ICP characteristics:
   - Company size match: +20 points
   - Industry match: +15 points  
   - Job title match: +25 points
   - Tech stack indicators: +10 points

## 📧 Email Marketing Integration (20 minutes)

### **Step 1: Generate Email Sequences**

Use the [Email Campaign Automation Prompt](../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Email-Campaign-Automation.md):

```
Create a 5-email welcome sequence for HubSpot automation:

ICP: [Your top ICP from earlier]
Product: [Your product/service]
Goal: Nurture leads to book a demo

Format each email as:
Subject Line: [Subject]
Preview Text: [Preview]  
Email Body: [Body with HubSpot personalization tokens]
CTA: [Clear call-to-action]
Send Delay: [Days after previous email]
```

### **Step 2: Build HubSpot Email Sequences**

1. Go to **Marketing > Email > Sequences**
2. Create new sequence
3. For each email:
   - Use AI-generated subject lines
   - Insert personalization tokens: `{{contact.firstname}}`, `{{contact.company}}`
   - Add AI-generated CTAs
   - Set delays as recommended by AI

### **Step 3: Create Smart Content**

1. Go to **Marketing > Email > Create Email**
2. Use **Smart Content** feature
3. Create variations for each ICP:
   - Different pain points
   - Industry-specific examples
   - Customized CTAs

**Example Smart Content Rules:**
```
If ICP_Category = "Tech_Startup" → Show startup case studies
If ICP_Category = "Enterprise" → Show enterprise security features  
If ICP_Category = "Agency" → Show client management benefits
```

## 🔄 Workflow Automation (25 minutes)

### **Step 1: Create ICP Classification Workflow**

1. Go to **Automation > Workflows**
2. Create **Contact-based workflow**
3. Enrollment trigger: "Contact is created"
4. Add actions:

```
IF Company Size = 25-100 employees 
AND Industry = Technology
AND Job Title contains "Marketing" OR "Growth"
THEN Set ICP_Category = "Tech_Startup"
AND Set ICP_Score = 8
AND Add to list "ICP1_Prospects"
```

### **Step 2: Content Personalization Workflow**

Create workflow that triggers personalized content:

1. **Trigger**: Contact visits pricing page
2. **Condition**: Check ICP_Category  
3. **Action**: Send personalized email based on ICP
4. **Follow-up**: Add to appropriate nurture sequence

### **Step 3: Lead Qualification Workflow**

1. **Trigger**: Form submission or meeting booking
2. **AI Enhancement**: Use [Lead Qualification Prompt](../04_Demand-&-Lead-Generation-&-Growth/Outbound-&-ABM/Lead-Qualification-Automation.md) 
3. **Action**: Score and route to appropriate sales rep

## 📊 Reporting & Analytics Setup (10 minutes)

### **Custom Dashboard Creation**

1. Go to **Reports > Dashboards**
2. Create "AI Marketing Performance" dashboard
3. Add these reports:
   - ICP conversion rates by category
   - Email performance by AI-generated content
   - Lead scoring accuracy
   - Content engagement by personalization

### **Key Metrics to Track**

```
📈 ICP Performance
- Conversion rate by ICP category
- Average deal size by ICP
- Sales cycle length by ICP

📧 Email Performance  
- Open rates for AI-generated subject lines
- Click rates for AI-generated CTAs
- Sequence completion rates

🎯 Content Performance
- Page views for personalized content
- Form conversions by content type
- Blog engagement from AI-generated posts
```

## 🔗 Advanced Integrations

### **Zapier Connections**

Connect HubSpot to AI tools for real-time automation:

1. **Trigger**: New contact in HubSpot
2. **Action**: Run ICP analysis prompt in ChatGPT
3. **Result**: Update HubSpot contact with AI insights

### **HubSpot API Integration**

For advanced users, use HubSpot's API to:
- Automatically generate personalized content
- Update contact properties with AI analysis
- Trigger workflows based on AI recommendations

## 🛠️ Maintenance & Optimization

### **Weekly Tasks (10 minutes)**
- Review ICP scoring accuracy
- Update email sequences based on performance
- Analyze content engagement metrics

### **Monthly Tasks (30 minutes)**  
- Refresh AI prompts with new data
- Update ICP criteria based on customer feedback
- Optimize workflows and automation rules

### **Quarterly Tasks (60 minutes)**
- Complete performance analysis
- Update buyer personas with AI insights
- Plan new automation sequences

## 🚨 Troubleshooting

### **Common Issues & Solutions**

**Problem**: AI content doesn't match HubSpot formatting
**Solution**: Add specific formatting instructions to prompts:
```
Format for HubSpot email:
- Use {{contact.firstname}} for personalization
- Keep paragraphs under 3 sentences
- Include clear CTA buttons
- Optimize for mobile viewing
```

**Problem**: Workflows not triggering correctly
**Solution**: Check enrollment criteria and add debug actions to track workflow execution

**Problem**: Lead scoring seems inaccurate  
**Solution**: Review scoring criteria monthly and adjust based on actual conversion data

**Problem**: Low email engagement despite AI content
**Solution**: A/B test AI-generated vs. traditional content, optimize based on results

## 📈 Expected Results

### **Week 1-2**: Foundation
- ✅ ICP classification automated
- ✅ Basic personalization active
- ✅ Lead scoring implemented

### **Month 1**: Optimization  
- 📈 25% improvement in email open rates
- 📈 40% better lead qualification accuracy
- 📈 20% increase in content engagement

### **Month 2-3**: Scale
- 📈 50% reduction in manual marketing tasks
- 📈 30% improvement in MQL to SQL conversion
- 📈 2x increase in personalized content creation speed

## 🎓 Next Steps

1. **Master the Basics**: Ensure all setup steps are complete
2. **Expand Integration**: Add social media and content marketing automation
3. **Advanced Features**: Implement predictive lead scoring and AI content generation
4. **Scale**: Apply learnings to other marketing tools and channels

---

## 🆘 Need Help?

**Setup Issues?** [Open a support ticket](https://github.com/AICMO/Marketing-Prompt-Collection/issues)

**Want Advanced Features?** Check our [Advanced HubSpot Workflows](./hubspot-advanced.md) *(Coming Soon)*

**Integration Success?** Share your results with the community!

---

*This integration typically increases marketing efficiency by 300% and lead quality by 150% within 60 days.*