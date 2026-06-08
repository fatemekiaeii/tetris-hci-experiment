# Tetris HCI Experiment — Interface Variations

A custom web-based experimental platform developed to study **automaticity 
disruption and recovery** following interface updates. This platform was used 
in a longitudinal eye-tracking study examining how users re-habituate after 
software changes disrupt established interaction routines.

## Research Context

Modern digital systems update continuously, yet each interface change can 
disrupt the automatic interaction patterns users have built through repeated 
use. This experiment investigates the cognitive and behavioral dynamics of 
that disruption — specifically how visual attention, motor efficiency, and 
task performance reorganize following controlled interface updates.

The Tetris paradigm was selected because it requires continuous visual 
monitoring, rapid motor coordination, and repeated interaction cycles — 
conditions under which automatic behavior develops quickly and becomes 
measurable through eye-tracking and interaction-log data.

## Experimental Design

The study employed a **mixed longitudinal design**:
- **Within-subjects**: All participants completed a baseline phase followed 
  by two successive post-update phases (10 minutes each)
- **Between-subjects**: Participants were randomly assigned to a control 
  condition (generic update notification) or a guidance condition 
  (descriptive update information)
- **Counterbalancing**: Participants were assigned to one of six update 
  sequences (S1–S6) varying the order and combination of interface changes

### Interface Dimensions Manipulated
Three dimensions of interaction were systematically varied across update phases:

| Dimension | Variations |
|---|---|
| Spatial orientation | Vertical / Horizontal |
| Motor mapping | Direct / Reversed controls |
| Information access | Icon-based / Menu-based |

### Interface Components
Each interface consisted of three regions used as spatial referents for 
gaze-transition analysis:
- **Game grid** — central area where pieces descended and were placed
- **Preview window** — displayed the upcoming piece
- **Score panel** — tracked cumulative task performance

## Interface Variations
interfaces/
├── C2_vertical_direct.html         # Vertical layout, direct control mapping
├── C3_vertical_reverse.html        # Vertical layout, reversed control mapping
├── C4_vertical_reverse_alt.html    # Vertical layout, reversed (alternative)
├── C5_horizontal_direct.html       # Horizontal layout, direct control mapping
├── C6_horizontal_direct_alt.html   # Horizontal layout, direct (alternative)
├── C7_horizontal_reverse.html      # Horizontal layout, reversed control mapping
└── C8_horizontal_reverse_alt.html  # Horizontal layout, reversed (alternative)
## Participants

- 52 participants recruited through the HEC Montréal participant panel
- Ethics approval obtained from the HEC Montréal Research Ethics Committee
- Eye-tracking analytic sample: 1,229 observations
- Interaction-log analytic sample: 45 participants, 1,511 observations

## Behavioral Measures

Multimodal data collected across all phases:
- **Gaze entropy** — attentional organization and predictability
- **Fixation patterns** — visual attention allocation across interface regions
- **Action-sequence entropy** — motor routine organization
- **Mouse trajectories** — motor efficiency and directness
- **Task performance** — score and piece-placement accuracy

## Related Repository

Data preprocessing and analysis pipelines: 
[behavioral-data-analysis](https://github.com/fatemekiaeii/behavioral-data-analysis)

## Citation

Kiaei Alamdari, F., Léger, P.-M., & Ortiz de Guinea, A. *Automaticity 
Disruption and Re-Habituation Following Interface Updates: A Longitudinal 
Eye-Tracking and Interaction-Log Study.* Working paper.

## Ethics

This study received ethics approval from the HEC Montréal Research Ethics 
Committee. All participants provided informed consent prior to participation.
