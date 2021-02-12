# START: This is the start of the Program

## Functionality: A user wants to wash their hands properly

## Objects/Data Structures
- person
- sink
- handSoap
- handTowel

## Steps
1. Turn on warm water on the sink
2. Apply one to two pumps of soap onto hands
3. Lather soap onto hands
4. Scrub hands together under warm water for > 20 seconds
5. Dry hands off with hand towel
6. Turn warm water off on the sink


## Code for Program
INIT (
- Create person
- Create sink
- Create handSoap
- Create handTowel
)

### Turn on sink

IF: sink is OFF, turn ON

### Apply handSoap

IF: No soap has been applied, apply to both hands

### Lather soap onto hands

IF: soap hasn't been lathered, rub hands together until completely covered in soap

### Scrub hands together under warm water

WHILE: hands are dirty/covered in soap, scrub together under warm water until clean

REPEAT: Until hands are clean

### Dry hands off with handTowel

WHILE: hands are wet, dry them off with handTowel

REPEAT: Until hands are dry

### Turn water off on the sink

IF: Sink is still on, turn water off

# END: This is the end of the Program