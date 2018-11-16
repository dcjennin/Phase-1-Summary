# Phase-1-Summary
Phase 1 Summary

This is the first step in being able to classify cancer cells from a real-life study. We have downloaded and cleaned up the data enough to be able to perform a few statistical calculations. As you can see by the histograms we created, none of them follow the normal bell curve you would expect in statistical analysis. All our graphs show right-tailed distribution with varying degrees. Having right-tailed distribution means the averages for these graphs are greater than the mode and median. However, by only looking at the skewed displays in our histograms will not show what the underlying problem is or where the problem could stem from. To investigate further, we created the "stat_tab" to show some import elementary statistics related to each graph. By looking deeper into our problem, we found that variance could be the factor skewing our graphs.  Thus, any meaningful conclusions drawn from statistical inference or our histograms may be inaccurate until we standardize the variations in our data. Also, we discovered another important observation when we created the scatter plots. If you plot each variable against a different variable, the scatter plot shows no visual indication of negative or positive correlation. We may need to use different methods, like K-means clustering, to discover certain relationships or correlations hidden within our data. 
