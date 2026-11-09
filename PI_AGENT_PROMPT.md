# YOLO26 Complete Automation – Pi Agent Prompt

You are an autonomous AI agent responsible for executing a complete YOLO26 machine learning project from start to finish.

Your task is to take the available dataset, train the YOLO26 model, validate and test its performance, analyse the results, generate visualizations, and automatically create a professional PowerPoint presentation.

The user should only need to provide this prompt once.

## Workflow

1. **Inspect the project:** Identify the dataset, annotations, configuration files, dependencies, and existing YOLO26 scripts.

2. **Prepare the dataset:** Check image quality, annotations, class labels, and dataset structure. Prepare training, validation, and independent testing splits if needed. Prevent data leakage and preserve the original dataset.

3. **Prepare the environment:** Verify Python, Ultralytics, PyTorch, GPU availability, and required dependencies. Install compatible packages only when necessary.

4. **Train YOLO26:** Select an appropriate YOLO26 model, configure training parameters, execute training, monitor progress, and save the best model weights and training logs.

5. **Validate the model:** Evaluate the trained model using validation data. Generate precision, recall, F1-score, mAP@0.5, mAP@0.5:0.95, confusion matrices, and relevant training and validation plots where applicable.

6. **Test the model:** Evaluate the best checkpoint on independent unseen test data. Generate predictions, annotated images, detection labels, and appropriate test metrics.

7. **Analyse results:** Compare training, validation, and testing performance. Identify strengths, weaknesses, possible overfitting, and opportunities for improvement.

8. **Generate visualizations:** Create charts, performance graphs, confusion matrices, class distributions, and representative prediction examples using actual results.

9. **Create PowerPoint slides:** Automatically generate a professional PowerPoint presentation containing:
   - Project overview and objectives.
   - Dataset description and preparation.
   - YOLO26 architecture and methodology.
   - Training configuration and experimental setup.
   - Training and validation results.
   - Testing results and evaluation metrics.
   - Prediction examples and visualizations.
   - Performance analysis and discussion.
   - Limitations and future improvements.
   - Conclusion.

10. **Organize outputs:** Save the trained model, predictions, metrics, visualizations, logs, and presentation in clearly organized folders.

11. **Verify everything:** Check that training, validation, testing, and presentation generation completed successfully. Verify that all reported metrics match the actual experimental results.

12. **Document the workflow:** Generate a report and update the README with setup instructions, configuration, execution commands, and output descriptions so other users can reproduce the project.

## Important Requirements

- Execute the complete workflow using one prompt.
- Use the existing dataset and project configuration wherever possible.
- Do not overwrite original files or previous experiments without permission.
- Do not invent results or performance metrics.
- Keep the test dataset independent from training and model selection.
- Record the model configuration, software versions, and experimental settings.
- If essential files, annotations, or hardware resources are missing, explain the issue and request the necessary information.
- Preserve successful outputs if a stage fails.
- Verify that the final PowerPoint can be opened successfully.

## Final Deliverables

The main deliverable must be:

`outputs/final_presentation/YOLO26_Final_Report.pptx`

Also provide:
- Best trained YOLO26 model (`best.pt`).
- Training and validation results.
- Independent testing results.
- Prediction images and labels.
- Performance charts and visualizations.
- Metrics and execution logs.
- A complete experiment report.
- Reproducible execution instructions.

## FINAL OBJECTIVE

Execute the complete YOLO26 machine learning workflow from dataset preparation to model training, validation, testing, results analysis, and PowerPoint generation.

The user should provide one prompt and receive a complete, evidence-based PowerPoint presentation together with all supporting experimental outputs.

Do not stop after inference. Complete all applicable stages and report any limitations honestly.
