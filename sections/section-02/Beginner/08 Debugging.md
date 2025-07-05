# 08 Debugging

[Debugging Video](https://www.youtube.com/watch?v=Gxe_RfCRH-o&ab_channel=n8n)

- [x] Watched video

## Debugging in n8n Workflows

Debugging in n8n involves identifying and fixing issues that prevent workflows from running correctly. Here's how debugging works in n8n:

### Execution Logs and Error Tracking

When a workflow runs, n8n provides detailed execution logs that show:

- Which nodes executed successfully
- Which nodes failed and why
- The exact data that flowed through each node
- Error messages with specific details about what went wrong

### Node-Level Debugging

You can click on any node in your workflow to see:

- The input data that node received
- The output data it produced
- Any error messages or warnings
- Execution time and performance metrics

### Common Debugging Steps

1. **Check Execution Logs**: Look at the execution history to see where the workflow failed
2. **Inspect Node Data**: Click on nodes to see what data they processed
3. **Review Error Messages**: Read error details to understand the specific problem
4. **Test Individual Nodes**: Run nodes in isolation to verify they work correctly
5. **Check Node Configuration**: Ensure all required fields are filled correctly

### Debugging Tools

- **Manual Execution**: Run workflows step-by-step to identify issues
- **Data Preview**: See exactly what data each node processes
- **Error Workflows**: Set up dedicated workflows to handle and log errors
- **Test Data**: Use sample data to verify workflow logic before using real data

### Troubleshooting Common Issues

- **API Errors**: Check credentials, endpoints, and request formats
- **Data Format Issues**: Ensure data structure matches what nodes expect
- **Connection Problems**: Verify network access and authentication
- **Logic Errors**: Review conditional statements and data transformations

Debugging in n8n is about systematically identifying where workflows break down and fixing the underlying issues to ensure reliable automation.

### Key Debugging Features

#### 1. Execution Logs

- Real-time visibility into workflow execution

#### 2. Node Inspection

- Click on any node to view its execution details

#### 3. Data Preview

- Preview data structure before and after each node

### Debugging Techniques

#### 1. Step-by-Step Execution

- Use the "Execute Workflow" button to run workflows manually

#### 2. Data Validation

- Check data types and formats at each step

#### 3. Error Analysis

- Read error messages carefully for specific details

### Best Practices for Debugging

#### 1. Start Small

- Test individual nodes before building complex workflows

#### 2. Use Test Data

- Create sample datasets for testing

#### 3. Document Issues

- Keep notes of common problems and solutions

#### 4. Use Debug Nodes

- Add "Set" nodes to log intermediate data

### Common Debugging Scenarios

#### 1. API Connection Issues

- Verify API keys and authentication

#### 2. Data Format Problems

- Ensure data structure matches node requirements

#### 3. Workflow Logic Errors

- Review conditional logic and filters

### Implementation

During the video we have created a simple workflow receiving new user we had to check if email and / or id was given and if so to confirm or if not to check what is missing and do an error.

simple example can be found here: [Debugging Workflow Example](link-to-be-added)
