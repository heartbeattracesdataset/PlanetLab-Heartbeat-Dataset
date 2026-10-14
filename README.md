cat > README.md <<'EOF'
# PlanetLab Heartbeat Dataset

Heartbeat-trace dataset organized for hierarchical distributed systems research.

## Dataset hierarchy

- Root9/node_5.csv
- Root9/node_6.csv
- Root9/node_7.csv
- Root9/node_5/ — six child CSV files
- Root9/node_6/ — six child CSV files
- Root9/node_7/ — six child CSV files
- Root9/ground_truth_manifest.json

## CSV fields

Node_ID, S_NUM, Send_T(ms), Rec_T(ms), Hop, Inter_Arrival_Send(ms), Inter_Arrival_Recv(ms)

## Sample data

See sample_data/node_5_sample.csv.

## Full dataset

Full dataset archives will be published separately, preserving the original folder hierarchy.

## Ground truth

The included manifest describes topology. Its faults array is empty and does not provide validated failure labels.
EOF
