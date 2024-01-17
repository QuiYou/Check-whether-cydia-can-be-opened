 + (CXDefenseReasonType)hasCydiaInstalled {
 return [[UIApplication sharedApplication] canOpenURL:[NSURL URLWithString:@"cydia://"]] ? CXDefenseReasonTypeCydiaInstalled : CXDefenseReasonTypeNone;
 }
