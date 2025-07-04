# 07 Error handling

[Error handling Video](https://www.youtube.com/watch?v=XEUVl3bbMhI&ab_channel=n8n)

- [x] Watched video

## Execution Logs in n8n Workflows

Execution logs in n8n provide real-time visibility into how your workflows are running, showing each step's status, data flow, and any errors that occur. These logs display the input and output data for each node, making it easy to trace the execution path and identify where issues might arise. When a workflow runs, you can click on any node to see its execution details, including the exact data that was processed and any error messages that were generated. This debugging capability is essential for troubleshooting workflow issues and understanding how data transforms as it moves through your automation pipeline.

## Error handling in n8n Workflows

Error handling in n8n is crucial for building reliable automations. It's important to know when your workflows fail so you can respond appropriately. n8n provides several ways to handle errors:

- **Error Workflow:** You can configure a dedicated Error Workflow that is automatically executed whenever your main workflow fails. This is set up per workflow from the settings tab. The Error Workflow can notify you, log the error, or trigger recovery actions.
- **Try-Catch Node:** The Try-Catch node allows you to wrap operations that might fail. The "Try" section contains nodes that could produce errors, while the "Catch" section handles any errors with custom logic or fallback steps.
- **Error Details:** When an error occurs, n8n provides detailed information such as error messages and stack traces. This helps you understand what went wrong and implement the right recovery mechanisms.

By combining these features, you can ensure your workflows are robust, can recover from failures, and provide visibility into issues as they happen.
