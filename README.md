## 🐞 Bug Fixes Implemented

1. **Double Fetch Issue**
   - Removed duplicate data loading effect and added fetch guard.

2. **Undo Snackbar Bug**
   - Reset deleted task state after snackbar closes.

3. **Unstable Sorting**
   - Implemented deterministic sorting using ROI, priority, and title.

4. **Dialog Overlap Issue**
   - Prevented event bubbling for Edit/Delete actions.

5. **ROI Calculation Errors**
   - Added safe ROI validation and formatting to avoid NaN/Infinity.
