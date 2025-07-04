# 07 Error handling

[Error handling Video](https://www.youtube.com/watch?v=XEUVl3bbMhI&ab_channel=n8n)

- [x] Watched video

## Execution Logs in n8n Workflows

Execution logs in n8n provide real-time visibility into how your workflows are running, showing each step's status, data flow, and any errors that occur. These logs display the input and output data for each node, making it easy to trace the execution path and identify where issues might arise. When a workflow runs, you can click on any node to see its execution details, including the exact data that was processed and any error messages that were generated. This debugging capability is essential for troubleshooting workflow issues and understanding how data transforms as it moves through your automation pipeline.

## Error handling in n8n Workflows

Error handling in n8n is primarily done through the Try-Catch node, which allows you to execute operations that might fail and handle errors gracefully. The Try section contains nodes that might produce errors, while the Catch section handles any errors that occur with custom logic and fallback options. When errors happen, you can access error details, messages, and stack traces to understand what went wrong and implement appropriate recovery mechanisms. This ensures your workflows continue running even when individual operations fail, making your automations more robust and reliable.

## Notes

todo
