# IoTComplianceAnalysis-BERT
Version information:
spaCy version    3.2.2                         
Platform         Windows-10

Python version   3.7.4  

Need the following directories/files created:
/ext/combined_tables
/ext/plaintext_policies (place all the policy text files here to be analyzed)
/ext/input/policySubsets/1.txt (copy names of all the text files present in the folder above to this file) 
/ext/output/policy (pickle files will be generated here as a result of running this application)
/ext/datasets/1.txt (copy the names of the pickle files to this file that were generated under the folder above)
/ext/output/analytics
/ext/output/db/
/ext/output/log_data
/ext/data/flows.csv (your file containing the results of app data analysis and these columns = ['package_name', 'app_name', 'version_name', 'version_code', 'data_type', 'dest_domain', 'dest_ip', 'arb_number', 'privacy_policy'])


Run the files in the following order:
PatternExtractionNotebook
ConsistencyAnalysisNotebook
RemoveSameSentenceContradictionsNotebook
DisclosureClassificationNotebook
