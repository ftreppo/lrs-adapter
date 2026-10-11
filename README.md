# LRS Adapter

Portable, provider-neutral LRS/dyslexia learning-material adapter with assessment safeguards, a PolicyPack interface, tests and documentation.

**Status:** `0.1.0-alpha.1` — standalone extraction baseline.

## Core

- [Portable Adapter instruction](adapter/LRS_ADAPTER_GENERIC_v0.1.md)
- [Standalone contract](specifications/contract-v0.1.md)
- [PolicyPack schema](specifications/PolicyPack.schema.json)
- [Synthetic PolicyPack fixture](fixtures/policy-pack.synthetic.json)
- [Conformance tests](tests/test_generic_adapter_contract.py)

The generic Adapter does **not** require DSM-LRS, MindMap, Notion, Google Drive, a specific school, or a specific identity/storage provider.

An integrating product may provide an optional provider-neutral PolicyPack.

## Community Adapter Lab

### Deutsch

Du kannst ein anonymisiertes Adapter-Beispiel zur Analyse einreichen:

**[Adapter-Beispiel einreichen](https://github.com/ftreppo/lrs-adapter/issues/new?template=adapter-example.yml)**

Keine personenbezogenen oder geschützten Daten. Rohe Submissions werden geprüft und werden nicht automatisch zu Adapter-Regeln oder kanonischen Beispielen.

### Italiano

Puoi inviare un esempio anonimizzato dell'Adapter per l'analisi:

**[Invia un esempio dell'Adapter](https://github.com/ftreppo/lrs-adapter/issues/new?template=adapter-example.yml)**

Niente dati personali o protetti. Le submission grezze vengono revisionate e non diventano automaticamente regole dell'Adapter o esempi canonici.

### English

You can submit an anonymized Adapter example for analysis:

**[Submit an Adapter Example](https://github.com/ftreppo/lrs-adapter/issues/new?template=adapter-example.yml)**

No personal or protected data. Raw submissions are reviewed and do not automatically become Adapter rules or canonical examples.

See [Community Adapter Lab](docs/community/COMMUNITY_ADAPTER_LAB.md).

## Independence

Allowed dependency direction:

```text
DSM-LRS or another product  ──►  lrs-adapter
```

Not allowed:

```text
lrs-adapter  ──►  DSM-LRS private/project runtime
```

## License

Apache License 2.0.
