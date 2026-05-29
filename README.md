# GhostShark
An ONT Remora Model to distinguish between Thymine and Uracil

## Usage
Assuming a `bam` file generated through ONT Dorado with the `--emit-moves` flag that is then sorted and indexed, alongside the pod5 file the `bam` was generated from, run the command `remora infer from_pod5_and_bam POD5_FILE BAM_FILE --model GhostShark/model_best.pt --out-bam OUTPUT_BAM --device 0`.
