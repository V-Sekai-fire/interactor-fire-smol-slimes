# interactor-fire-smol-slimes

A plan for a twenty-tracker wireless inertial motion-capture suit, for animating game characters.

## Use

The plan splits the trackers across two receivers, one for the main body points and one for the extra points that add accuracy. The figure shows where each tracker sits on the body. The two scripts score candidate receiver and tracker boards with STAR voting on cost, size and signal range.

![Tracker placements](slime_placements.png)

## Build and run

```sh
pip install -r requirements.txt
python smol_slime_tracker.py
python smol_slime_reciever.py
```

## Licence

Apache-2.0. See `LICENSE`.
