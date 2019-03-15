fetch的时候，状态是everything up to date，这个是没问题的。merge的时候抛了个异常。异常信息是：An internal error occurred during: "Merging with refs/remotes/origin/master". 
Exception caught during execution of merge command. org.eclipse.jgit.errors.NoMergeBaseException: No merge base could be determined. Reason=CONFLICTS_DURING_MERGE_BASE_CALCULATION. "More than 200 merge bases for: 
 a 7abff2535bbd9e52297134046529787edaeb4308 
 b fe1827998b9347e834264aaf2a0415d7c37ec29a found: 

