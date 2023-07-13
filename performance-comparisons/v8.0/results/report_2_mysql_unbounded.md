### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.DeleteForPost | avg | 21ms | 47ms | 26ms | 123.13
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 36ms | 63ms | 27ms | 76.03
| JobStore.UpdateStatusOptimistically | avg | 17ms | 29ms | 12ms | 68.59
| PostStore.GetPostReminders | avg | 40ms | 66ms | 26ms | 65.32
| FileInfoStore.AttachToPost | avg | 30ms | 48ms | 18ms | 59.96
| TeamStore.SaveMember | avg | 108ms | 157ms | 49ms | 45.29
| PreferenceStore.DeleteCategoryAndName | avg | 28ms | 40ms | 12ms | 43.50
| FileInfoStore.Save | avg | 25ms | 34ms | 9ms | 36.18
| ThreadStore.MarkAsRead | avg | 18ms | 24ms | 6ms | 33.21
| SessionStore.Remove | avg | 18ms | 24ms | 6ms | 32.50
| ChannelStore.CreateSidebarCategory | avg | 145ms | 192ms | 47ms | 32.31
| ChannelStore.UpdateSidebarChannelsByPreferences | avg | 16ms | 21ms | 5ms | 30.52
| SessionStore.UpdateLastActivityAt | avg | 20ms | 26ms | 6ms | 30.49
| PostStore.Update | avg | 65ms | 84ms | 19ms | 29.38
| PostStore.Save | avg | 58ms | 73ms | 15ms | 25.71
| PluginStore.Delete | avg | 12ms | 15ms | 3ms | 25.22
| ThreadStore.UpdateMembership | avg | 20ms | 25ms | 5ms | 24.77
| ReactionStore.Save | avg | 67ms | 81ms | 14ms | 20.88
| ChannelStore.UpdateLastViewedAt | avg | 35ms | 42ms | 7ms | 19.73
| JobStore.UpdateStatus | avg | 16ms | 19ms | 3ms | 19.34
| StatusStore.UpdateLastActivityAt | avg | 21ms | 25ms | 4ms | 18.90
| ThreadStore.MaintainMembership | avg | 43ms | 51ms | 8ms | 18.67
| PluginStore.SetWithOptions | avg | 27ms | 32ms | 5ms | 18.52
| ChannelStore.IncrementMentionCount | avg | 17ms | 20ms | 3ms | 18.12
| UserStore.Update | avg | 48ms | 56ms | 8ms | 16.71
| ProductNoticesStore.ClearOldNotices | avg | 13ms | 15ms | 2ms | 15.85
| UserStore.InvalidateProfilesInChannelCacheByUser | avg | 295ms | 341ms | 46ms | 15.61
| ClusterDiscoveryStore.SetLastPingAt | avg | 26ms | 30ms | 4ms | 15.50
| ThreadStore.MarkAllAsReadByTeam | avg | 30ms | 34ms | 4ms | 13.51
| ChannelMemberHistoryStore.LogJoinEvent | avg | 17ms | 19ms | 2ms | 12.12
| PostStore.GetPostIdBeforeTime | avg | 19ms | 21ms | 2ms | 10.42
| ThreadStore.MarkAllAsReadByChannels | avg | 20ms | 22ms | 2ms | 10.14
| ProductNoticesStore.View | avg | 92ms | 101ms | 9ms | 9.74
| UserStore.UpdateFailedPasswordAttempts | avg | 21ms | 23ms | 2ms | 9.48
| PostStore.SetPostReminder | avg | 67ms | 73ms | 6ms | 9.01
| PreferenceStore.Save | avg | 58ms | 63ms | 5ms | 8.62
| PostStore.SearchPostsForUser | avg | 223ms | 236ms | 13ms | 5.83
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| JobStore.UpdateStatusOptimistically | p99 | 90ms | 300ms | 210ms | 233.76
| ProductNoticesStore.ClearOldNotices | p99 | 25ms | 49ms | 24ms | 96.86
| TeamStore.SaveMember | p99 | 451ms | 744ms | 293ms | 64.95
| PreferenceStore.DeleteCategoryAndName | p99 | 243ms | 355ms | 112ms | 46.16
| FileInfoStore.AttachToPost | p99 | 244ms | 353ms | 109ms | 44.65
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 393ms | 478ms | 85ms | 21.65
| PostStore.GetPostReminders | p99 | 387ms | 450ms | 63ms | 16.26
| UserStore.InvalidateProfilesInChannelCacheByUser | p99 | 1.961s | 2.228s | 267ms | 13.61
| SessionStore.Remove | p99 | 183ms | 204ms | 21ms | 11.47
| PluginStore.Delete | p99 | 152ms | 167ms | 15ms | 9.86
| ThreadStore.MarkAsRead | p99 | 178ms | 195ms | 17ms | 9.53
| SessionStore.UpdateLastActivityAt | p99 | 203ms | 218ms | 15ms | 7.38
| UserStore.UpdateUpdateAt | p99 | 137ms | 146ms | 9ms | 6.57
| ChannelStore.GetMembers | p99 | 1.494s | 1.589s | 95ms | 6.36
| BotStore.Get | p99 | 382ms | 400ms | 18ms | 4.71
| ChannelStore.IncrementMentionCount | p99 | 201ms | 210ms | 9ms | 4.49
| FileInfoStore.Save | p99 | 231ms | 240ms | 9ms | 3.90
| ChannelStore.CreateSidebarCategory | p99 | 928ms | 962ms | 34ms | 3.67
| PostStore.Save | p99 | 479ms | 496ms | 17ms | 3.55
| JobStore.Save | p99 | 235ms | 243ms | 8ms | 3.41
| ChannelStore.UpdateSidebarCategories | p99 | 2.314s | 2.39s | 76ms | 3.28
| FileInfoStore.DeleteForPost | p99 | 96ms | 99ms | 3ms | 3.12
| PostStore.Update | p99 | 454ms | 463ms | 9ms | 1.98
| UserStore.UpdateFailedPasswordAttempts | p99 | 215ms | 219ms | 4ms | 1.86
| ProductNoticesStore.View | p99 | 834ms | 845ms | 11ms | 1.32
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Save | avg | 4ms | 0s | -4ms | -105.77
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 41ms | 0s | -41ms | -100.91
| PostAcknowledgementStore.Save | avg | 52ms | 0s | -52ms | -100.89
| LinkMetadataStore.Save | avg | 15ms | 0s | -15ms | -100.73
| PostPriorityStore.GetForPost | avg | 45ms | 0s | -45ms | -100.65
| ChannelStore.GetMembersForUserWithPagination | avg | 126ms | 0s | -126ms | -100.38
| ChannelStore.GetByNameIncludeDeleted | avg | 102ms | 0s | -102ms | -100.37
| PostAcknowledgementStore.GetForPost | avg | 46ms | 0s | -46ms | -100.34
| PostStore.GetTopDMsForUserSince | avg | 161ms | 0s | -161ms | -100.29
| ProductNoticesStore.GetViews | avg | 133ms | 0s | -133ms | -100.24
| DraftStore.GetDraftsForUser | avg | 100ms | 0s | -100ms | -100.23
| SessionStore.AnalyticsSessionCount | avg | 142ms | 0s | -142ms | -100.16
| ComplianceStore.MessageExport | avg | 349ms | 0s | -349ms | -100.14
| PostAcknowledgementStore.GetForPosts | avg | 45ms | 0s | -45ms | -100.12
| CommandStore.AnalyticsCommandCount | avg | 121ms | 0s | -121ms | -100.08
| WebhookStore.AnalyticsIncomingCount | avg | 128ms | 0s | -128ms | -100.08
| ThreadStore.GetTopThreadsForUserSince | avg | 390ms | 0s | -390ms | -100.04
| ThreadStore.GetTopThreadsForTeamSince | avg | 1.383s | 0s | -1.383s | -100.03
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 873ms | 0s | -873ms | -100.02
| UserStore.AnalyticsActiveCount | avg | 517ms | 0s | -517ms | -100.01
| ReactionStore.GetTopForUserSince | avg | 3.923s | 0s | -3.923s | -100.00
| ReactionStore.GetTopForTeamSince | avg | 19.932s | 0s | -19.932s | -100.00
| ChannelStore.GetTopChannelsForTeamSince | avg | 29.239s | 0s | -29.239s | -100.00
| ChannelStore.GetTopInactiveChannelsForUserSince | avg | 1.448s | 0s | -1.448s | -99.97
| FileInfoStore.Search | avg | 109ms | 0s | -109ms | -99.90
| ChannelStore.AnalyticsTypeCount | avg | 380ms | 0s | -380ms | -99.89
| JobStore.GetAllByTypePage | avg | 102ms | 0s | -102ms | -99.85
| ChannelStore.PostCountsByDuration | avg | 184ms | 0s | -184ms | -99.82
| UserStore.AnalyticsGetInactiveUsersCount | avg | 99ms | 0s | -99ms | -99.78
| WebhookStore.AnalyticsOutgoingCount | avg | 77ms | 0s | -77ms | -99.64
| ChannelStore.GetMemberCountsByGroup | avg | 32ms | 0s | -32ms | -99.63
| DraftStore.Get | avg | 58ms | 0s | -58ms | -99.61
| GroupStore.GetGroupsAssociatedToChannelsByTeam | avg | 105ms | 0s | -105ms | -99.53
| ChannelStore.GetTopChannelsForUserSince | avg | 92ms | 0s | -92ms | -99.48
| PostStore.HasAutoResponsePostByUserSince | avg | 88ms | 0s | -88ms | -99.45
| LicenseStore.GetAll | avg | 40ms | 0s | -40ms | -99.42
| PostPriorityStore.GetForPosts | avg | 45ms | 0s | -45ms | -99.19
| ChannelStore.GetFileCount | avg | 179ms | 30ms | -149ms | -83.14
| ChannelStore.Get | avg | 17ms | 3ms | -14ms | -82.52
| JobStore.Get | avg | 155ms | 30ms | -125ms | -80.69
| TeamStore.GetChannelUnreadsForAllTeams | avg | 69ms | 14ms | -55ms | -79.82
| TeamStore.GetTeamsByUserId | avg | 50ms | 11ms | -39ms | -78.77
| JobStore.GetNewestJobByStatusesAndType | avg | 104ms | 22ms | -82ms | -78.54
| PreferenceStore.GetAll | avg | 85ms | 20ms | -65ms | -76.49
| UserTermsOfServiceStore.GetByUser | avg | 93ms | 23ms | -70ms | -75.56
| PostStore.GetEtag | avg | 40ms | 11ms | -29ms | -72.68
| TeamStore.GetAllPage | avg | 58ms | 16ms | -42ms | -72.13
| ThreadStore.GetTeamsUnreadForUser | avg | 94ms | 28ms | -66ms | -69.96
| ChannelStore.Autocomplete | avg | 494ms | 149ms | -345ms | -69.87
| ChannelStore.GetGuestCount | avg | 32ms | 10ms | -22ms | -68.69
| ChannelStore.GetChannels | avg | 93ms | 29ms | -64ms | -68.57
| CommandWebhookStore.Cleanup | avg | 37ms | 12ms | -25ms | -68.44
| JobStore.GetCountByStatusAndType | avg | 103ms | 33ms | -70ms | -68.24
| ChannelStore.GetPinnedPostCount | avg | 44ms | 15ms | -29ms | -65.99
| ChannelStore.GetMember | avg | 38ms | 13ms | -25ms | -65.47
| PostStore.GetPostReminderMetadata | avg | 96ms | 34ms | -62ms | -64.67
| PostStore.GetSingle | avg | 83ms | 30ms | -53ms | -64.17
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 220ms | 81ms | -139ms | -63.26
| ChannelStore.GetMembersForUser | avg | 87ms | 33ms | -54ms | -61.83
| UserStore.GetForLogin | avg | 66ms | 25ms | -41ms | -61.74
| ThreadStore.GetThreadUnreadReplyCount | avg | 107ms | 41ms | -66ms | -61.40
| PluginStore.Get | avg | 57ms | 22ms | -35ms | -61.03
| ChannelStore.GetMemberCount | avg | 83ms | 33ms | -50ms | -60.56
| PostStore.GetPostsByThread | avg | 93ms | 37ms | -56ms | -60.41
| ThreadStore.Get | avg | 95ms | 38ms | -57ms | -60.27
| UserStore.GetByUsername | avg | 93ms | 37ms | -56ms | -59.97
| ChannelStore.GetMany | avg | 67ms | 27ms | -40ms | -59.32
| ChannelStore.SearchGroupChannels | avg | 103ms | 42ms | -61ms | -59.09
| ChannelStore.GetMembersInfoByChannelIds | avg | 100ms | 41ms | -59ms | -59.07
| StatusStore.GetByIds | avg | 126ms | 52ms | -74ms | -58.81
| TeamStore.Get | avg | 66ms | 27ms | -39ms | -58.74
| PostStore.GetPosts | avg | 75ms | 31ms | -44ms | -58.72
| ThreadStore.GetTotalUnreadMentions | avg | 72ms | 30ms | -42ms | -58.61
| PluginStore.List | avg | 61ms | 26ms | -35ms | -57.62
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 71ms | 30ms | -41ms | -57.54
| TeamStore.GetMember | avg | 64ms | 27ms | -37ms | -57.42
| ChannelStore.GetAllChannelMembersForUser | avg | 25ms | 11ms | -14ms | -57.09
| TeamStore.GetTeamsForUser | avg | 74ms | 32ms | -42ms | -57.00
| ThreadStore.GetTotalUnreadThreads | avg | 72ms | 31ms | -41ms | -56.99
| PostStore.AnalyticsPostCount | avg | 7.854s | 3.38s | -4.474s | -56.97
| ThreadStore.GetTotalThreads | avg | 71ms | 31ms | -40ms | -56.55
| UserStore.GetUnreadCountForChannel | avg | 76ms | 33ms | -43ms | -56.51
| UserStore.Search | avg | 253ms | 110ms | -143ms | -56.44
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 62ms | 27ms | -35ms | -56.35
| PreferenceStore.Get | avg | 75ms | 33ms | -42ms | -56.29
| UserStore.GetAllProfiles | avg | 82ms | 36ms | -46ms | -56.20
| PostStore.GetPostsAfter | avg | 91ms | 40ms | -51ms | -56.01
| UserStore.AutocompleteUsersInChannel | avg | 683ms | 301ms | -382ms | -55.89
| ThreadStore.GetThreadFollowers | avg | 81ms | 36ms | -45ms | -55.84
| UserStore.GetUnreadCount | avg | 75ms | 33ms | -42ms | -55.81
| ChannelStore.GetChannelsWithCursor | avg | 102ms | 45ms | -57ms | -55.79
| GroupStore.GetGroups | avg | 74ms | 33ms | -41ms | -55.78
| LinkMetadataStore.Get | avg | 59ms | 26ms | -33ms | -55.76
| UserStore.IsEmpty | avg | 20ms | 9ms | -11ms | -55.28
| PostStore.Get | avg | 204ms | 92ms | -112ms | -55.03
| StatusStore.Get | avg | 33ms | 15ms | -18ms | -54.83
| TeamStore.GetByName | avg | 73ms | 33ms | -40ms | -54.58
| ThreadStore.GetThreadsForUser | avg | 104ms | 48ms | -56ms | -53.97
| EmojiStore.GetMultipleByName | avg | 56ms | 26ms | -30ms | -53.95
| UserStore.GetProfilesByUsernames | avg | 80ms | 37ms | -43ms | -53.88
| ChannelStore.GetMembersForUserWithCursor | avg | 104ms | 48ms | -56ms | -53.80
| ChannelStore.GetByName | avg | 53ms | 25ms | -28ms | -53.20
| PostStore.GetPostsBefore | avg | 94ms | 44ms | -50ms | -53.04
| ChannelStore.GetPublicChannelsForTeam | avg | 121ms | 57ms | -64ms | -53.01
| UserStore.Count | avg | 211ms | 100ms | -111ms | -52.64
| TeamStore.GetMany | avg | 91ms | 43ms | -48ms | -52.50
| JobStore.GetAllByStatus | avg | 84ms | 40ms | -44ms | -52.26
| ThreadStore.GetThreadForUser | avg | 108ms | 52ms | -56ms | -52.04
| UserAccessTokenStore.GetByToken | avg | 85ms | 41ms | -44ms | -51.63
| ChannelStore.GetChannelsByUser | avg | 86ms | 42ms | -44ms | -51.17
| GroupStore.GetByName | avg | 32ms | 16ms | -16ms | -50.73
| PostStore.GetPostsSince | avg | 136ms | 67ms | -69ms | -50.70
| UserStore.GetProfilesInChannel | avg | 109ms | 54ms | -55ms | -50.36
| TokenStore.Cleanup | avg | 24ms | 12ms | -12ms | -49.98
| ChannelStore.GetTeamChannels | avg | 175ms | 88ms | -87ms | -49.76
| ChannelStore.GetMemberForPost | avg | 55ms | 28ms | -27ms | -49.38
| SessionStore.Save | avg | 89ms | 46ms | -43ms | -48.31
| FileInfoStore.Get | avg | 59ms | 31ms | -28ms | -47.49
| ChannelStore.AutocompleteInTeamForSearch | avg | 509ms | 268ms | -241ms | -47.36
| ChannelStore.GetChannelUnread | avg | 78ms | 41ms | -37ms | -47.25
| ThreadStore.GetMembershipForUser | avg | 73ms | 39ms | -34ms | -46.34
| TeamStore.AnalyticsTeamCount | avg | 35ms | 19ms | -16ms | -45.32
| SessionStore.GetSessionsExpired | avg | 43ms | 24ms | -19ms | -44.07
| WebhookStore.GetOutgoingByTeam | avg | 80ms | 46ms | -34ms | -42.54
| ChannelStore.GetSidebarCategory | avg | 147ms | 89ms | -58ms | -39.35
| ChannelStore.SaveMember | avg | 193ms | 119ms | -74ms | -38.39
| SystemStore.GetByName | avg | 19ms | 12ms | -7ms | -36.31
| BotStore.Get | avg | 43ms | 30ms | -13ms | -30.27
| ChannelStore.Save | avg | 147ms | 104ms | -43ms | -29.19
| JobStore.Save | avg | 31ms | 22ms | -9ms | -28.59
| UserStore.GetAllProfilesInChannel | avg | 817ms | 651ms | -166ms | -20.32
| StatusStore.UpdateExpiredDNDStatuses | avg | 68ms | 56ms | -12ms | -17.60
| ChannelStore.CreateDirectChannel | avg | 167ms | 145ms | -22ms | -13.19
| ChannelStore.CreateInitialSidebarCategories | avg | 100ms | 87ms | -13ms | -12.96
| ChannelStore.GetMembers | avg | 121ms | 110ms | -11ms | -9.11
| SessionStore.Get | avg | 38ms | 35ms | -3ms | -7.80
| PostStore.Delete | avg | 166ms | 157ms | -9ms | -5.43
| UserStore.Save | avg | 111ms | 105ms | -6ms | -5.43
| StatusStore.SaveOrUpdate | avg | 87ms | 84ms | -3ms | -3.44
| ChannelStore.UpdateSidebarCategories | avg | 340ms | 335ms | -5ms | -1.47
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| BotStore.Save | p99 | 5ms | 0s | -5ms | -101.01
| WebhookStore.AnalyticsOutgoingCount | p99 | 246ms | 0s | -246ms | -100.20
| DraftStore.GetDraftsForUser | p99 | 248ms | 0s | -248ms | -100.20
| FileInfoStore.Search | p99 | 249ms | 0s | -249ms | -100.20
| LinkMetadataStore.Save | p99 | 192ms | 0s | -192ms | -100.17
| ChannelStore.GetMembersForUserWithPagination | p99 | 448ms | 0s | -448ms | -100.11
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 478ms | 0s | -478ms | -100.10
| CommandStore.AnalyticsCommandCount | p99 | 248ms | 0s | -248ms | -100.10
| WebhookStore.AnalyticsIncomingCount | p99 | 248ms | 0s | -248ms | -100.10
| ProductNoticesStore.GetViews | p99 | 248ms | 0s | -248ms | -100.10
| SessionStore.AnalyticsSessionCount | p99 | 248ms | 0s | -248ms | -100.10
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 443ms | 0s | -443ms | -100.10
| PostPriorityStore.GetForPost | p99 | 457ms | 0s | -457ms | -100.08
| ChannelStore.AnalyticsTypeCount | p99 | 978ms | 0s | -978ms | -100.05
| PostStore.GetTopDMsForUserSince | p99 | 1.663s | 0s | -1.663s | -100.03
| ChannelStore.PostCountsByDuration | p99 | 2.088s | 0s | -2.088s | -100.02
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 2.939s | 0s | -2.939s | -100.01
| ReactionStore.GetTopForUserSince | p99 | 9.742s | 0s | -9.742s | -100.00
| ChannelStore.GetTopInactiveChannelsForUserSince | p99 | 4.747s | 0s | -4.747s | -100.00
| ThreadStore.GetTopThreadsForTeamSince | p99 | 8.925s | 0s | -8.925s | -100.00
| ReactionStore.GetTopForTeamSince | p99 | 10s | 0s | -10s | -100.00
| ComplianceStore.MessageExport | p99 | 970ms | 0s | -970ms | -100.00
| ChannelStore.GetTopChannelsForTeamSince | p99 | 10s | 0s | -10s | -100.00
| DraftStore.Get | p99 | 244ms | 0s | -244ms | -100.00
| ChannelStore.GetByNameIncludeDeleted | p99 | 244ms | 0s | -244ms | -100.00
| LicenseStore.GetAll | p99 | 232ms | 0s | -232ms | -100.00
| ThreadStore.GetTopThreadsForUserSince | p99 | 4.704s | 0s | -4.704s | -100.00
| PostPriorityStore.GetForPosts | p99 | 517ms | 0s | -517ms | -99.99
| UserStore.AnalyticsActiveCount | p99 | 987ms | 0s | -987ms | -99.99
| PostStore.HasAutoResponsePostByUserSince | p99 | 1.059s | 0s | -1.059s | -99.97
| ChannelStore.GetTopChannelsForUserSince | p99 | 1.127s | 0s | -1.127s | -99.96
| JobStore.GetAllByTypePage | p99 | 486ms | 0s | -486ms | -99.95
| PostAcknowledgementStore.Save | p99 | 412ms | 0s | -412ms | -99.94
| PostAcknowledgementStore.GetForPosts | p99 | 516ms | 0s | -516ms | -99.93
| PostAcknowledgementStore.GetForPost | p99 | 463ms | 0s | -463ms | -99.90
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 246ms | 0s | -246ms | -99.85
| ChannelStore.GetMemberCountsByGroup | p99 | 242ms | 0s | -242ms | -99.85
| JobStore.Get | p99 | 2.102s | 300ms | -1.802s | -85.74
| JobStore.GetCountByStatusAndType | p99 | 1.33s | 249ms | -1.081s | -81.28
| CommandWebhookStore.Cleanup | p99 | 241ms | 49ms | -192ms | -79.67
| ChannelStore.Get | p99 | 370ms | 87ms | -283ms | -76.49
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 824ms | 222ms | -602ms | -73.10
| JobStore.GetNewestJobByStatusesAndType | p99 | 885ms | 246ms | -639ms | -72.20
| PreferenceStore.GetAll | p99 | 881ms | 248ms | -633ms | -71.84
| StatusStore.UpdateExpiredDNDStatuses | p99 | 775ms | 240ms | -535ms | -69.03
| ChannelStore.GetFileCount | p99 | 1s | 310ms | -690ms | -69.01
| PostStore.GetPostReminderMetadata | p99 | 955ms | 311ms | -644ms | -67.43
| UserTermsOfServiceStore.GetByUser | p99 | 952ms | 314ms | -638ms | -66.99
| TeamStore.GetAllPage | p99 | 709ms | 237ms | -472ms | -66.59
| UserStore.Search | p99 | 2.046s | 728ms | -1.318s | -64.43
| StatusStore.GetByIds | p99 | 1.447s | 528ms | -919ms | -63.53
| ChannelStore.Autocomplete | p99 | 4.651s | 1.782s | -2.869s | -61.68
| TeamStore.GetTeamsByUserId | p99 | 499ms | 191ms | -308ms | -61.68
| PostStore.GetEtag | p99 | 573ms | 222ms | -351ms | -61.25
| ChannelStore.GetPinnedPostCount | p99 | 611ms | 238ms | -373ms | -61.02
| UserStore.GetUnreadCount | p99 | 902ms | 355ms | -547ms | -60.62
| PluginStore.Get | p99 | 744ms | 293ms | -451ms | -60.61
| UserStore.Count | p99 | 987ms | 390ms | -597ms | -60.52
| UserStore.AutocompleteUsersInChannel | p99 | 2.432s | 980ms | -1.452s | -59.70
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 2.244s | 905ms | -1.339s | -59.66
| ThreadStore.GetTeamsUnreadForUser | p99 | 1s | 404ms | -596ms | -59.60
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 864ms | 353ms | -511ms | -59.11
| PostStore.Get | p99 | 2.114s | 868ms | -1.246s | -58.94
| PostStore.GetSingle | p99 | 931ms | 385ms | -546ms | -58.65
| ChannelStore.GetChannels | p99 | 923ms | 383ms | -540ms | -58.50
| PostStore.GetPosts | p99 | 867ms | 364ms | -503ms | -58.03
| ChannelStore.GetMany | p99 | 865ms | 364ms | -501ms | -57.89
| TeamStore.GetMember | p99 | 782ms | 331ms | -451ms | -57.66
| TeamStore.Get | p99 | 835ms | 358ms | -477ms | -57.16
| ChannelStore.GetGuestCount | p99 | 484ms | 208ms | -276ms | -57.02
| ChannelStore.GetMember | p99 | 494ms | 213ms | -281ms | -56.84
| ThreadStore.Get | p99 | 976ms | 422ms | -554ms | -56.77
| PostStore.GetPostsByThread | p99 | 973ms | 423ms | -550ms | -56.50
| UserStore.GetForLogin | p99 | 788ms | 345ms | -443ms | -56.22
| ChannelStore.GetMembersForUser | p99 | 919ms | 408ms | -511ms | -55.63
| ThreadStore.GetThreadForUser | p99 | 1.3s | 579ms | -721ms | -55.45
| LinkMetadataStore.Get | p99 | 788ms | 351ms | -437ms | -55.44
| ChannelStore.GetMembersInfoByChannelIds | p99 | 982ms | 438ms | -544ms | -55.41
| UserStore.GetUnreadCountForChannel | p99 | 876ms | 391ms | -485ms | -55.38
| PluginStore.List | p99 | 487ms | 219ms | -268ms | -55.08
| GroupStore.GetGroups | p99 | 856ms | 388ms | -468ms | -54.64
| ThreadStore.GetThreadUnreadReplyCount | p99 | 992ms | 451ms | -541ms | -54.56
| ChannelStore.GetMemberCount | p99 | 940ms | 428ms | -512ms | -54.49
| PreferenceStore.Get | p99 | 876ms | 401ms | -475ms | -54.20
| EmojiStore.GetMultipleByName | p99 | 746ms | 342ms | -404ms | -54.12
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 776ms | 358ms | -418ms | -53.89
| ChannelStore.SearchGroupChannels | p99 | 960ms | 447ms | -513ms | -53.41
| PostStore.GetPostsAfter | p99 | 951ms | 443ms | -508ms | -53.39
| TeamStore.GetTeamsForUser | p99 | 880ms | 410ms | -470ms | -53.38
| UserStore.GetByUsername | p99 | 977ms | 460ms | -517ms | -52.91
| ChannelStore.GetChannelsWithCursor | p99 | 985ms | 466ms | -519ms | -52.68
| TeamStore.GetMany | p99 | 944ms | 450ms | -494ms | -52.35
| ThreadStore.GetTotalUnreadThreads | p99 | 847ms | 406ms | -441ms | -52.05
| ThreadStore.GetThreadFollowers | p99 | 911ms | 440ms | -471ms | -51.71
| ThreadStore.GetTotalUnreadMentions | p99 | 836ms | 404ms | -432ms | -51.71
| ChannelStore.GetMembersForUserWithCursor | p99 | 986ms | 477ms | -509ms | -51.62
| PostStore.GetPostsBefore | p99 | 938ms | 455ms | -483ms | -51.52
| SessionStore.GetSessionsExpired | p99 | 455ms | 222ms | -233ms | -51.21
| UserStore.GetAllProfiles | p99 | 916ms | 447ms | -469ms | -51.18
| JobStore.GetAllByStatus | p99 | 908ms | 444ms | -464ms | -51.11
| PostStore.GetPostsSince | p99 | 984ms | 482ms | -502ms | -51.04
| UserStore.GetProfilesByUsernames | p99 | 864ms | 423ms | -441ms | -51.02
| ThreadStore.GetThreadsForUser | p99 | 963ms | 473ms | -490ms | -50.88
| ChannelStore.GetPublicChannelsForTeam | p99 | 969ms | 477ms | -492ms | -50.75
| ChannelStore.GetChannelsByUser | p99 | 926ms | 457ms | -469ms | -50.67
| ChannelStore.GetAllChannelMembersForUser | p99 | 440ms | 218ms | -222ms | -50.45
| ThreadStore.GetTotalThreads | p99 | 818ms | 411ms | -407ms | -49.75
| SessionStore.Save | p99 | 897ms | 452ms | -445ms | -49.62
| TeamStore.GetByName | p99 | 869ms | 438ms | -431ms | -49.58
| TokenStore.Cleanup | p99 | 97ms | 49ms | -48ms | -49.48
| ChannelStore.GetSidebarCategory | p99 | 1.478s | 754ms | -724ms | -48.97
| ChannelStore.SaveMember | p99 | 1.819s | 936ms | -883ms | -48.53
| ThreadStore.GetMembershipForUser | p99 | 866ms | 448ms | -418ms | -48.25
| UserStore.GetProfilesInChannel | p99 | 955ms | 495ms | -460ms | -48.15
| ChannelStore.GetMemberForPost | p99 | 625ms | 326ms | -299ms | -47.82
| UserAccessTokenStore.GetByToken | p99 | 897ms | 472ms | -425ms | -47.40
| ChannelStore.GetChannelUnread | p99 | 864ms | 455ms | -409ms | -47.34
| WebhookStore.GetOutgoingByTeam | p99 | 885ms | 469ms | -416ms | -47.01
| ChannelStore.GetByName | p99 | 625ms | 334ms | -291ms | -46.55
| StatusStore.Get | p99 | 441ms | 238ms | -203ms | -45.98
| TeamStore.AnalyticsTeamCount | p99 | 459ms | 249ms | -210ms | -45.72
| FileInfoStore.Get | p99 | 667ms | 366ms | -301ms | -45.15
| UserStore.IsEmpty | p99 | 317ms | 175ms | -142ms | -44.80
| GroupStore.GetByName | p99 | 413ms | 234ms | -179ms | -43.30
| PostStore.Delete | p99 | 1.587s | 941ms | -646ms | -40.69
| ChannelStore.AutocompleteInTeamForSearch | p99 | 3.72s | 2.294s | -1.426s | -38.34
| ChannelStore.GetTeamChannels | p99 | 978ms | 615ms | -363ms | -37.12
| JobStore.UpdateStatus | p99 | 190ms | 130ms | -60ms | -31.58
| SystemStore.GetByName | p99 | 218ms | 154ms | -64ms | -29.30
| ChannelStore.Save | p99 | 989ms | 739ms | -250ms | -25.29
| SessionStore.Get | p99 | 393ms | 323ms | -70ms | -17.82
| UserStore.GetProfileByIds | p99 | 136ms | 112ms | -24ms | -17.60
| UserStore.GetAllProfilesInChannel | p99 | 4.822s | 3.986s | -836ms | -17.34
| JobStore.UpdateOptimistically | p99 | 228ms | 190ms | -38ms | -16.65
| PostStore.SearchPostsForUser | p99 | 1.7s | 1.452s | -248ms | -14.59
| PostStore.GetPostIdAfterTime | p99 | 207ms | 184ms | -23ms | -11.11
| StatusStore.SaveOrUpdate | p99 | 1.986s | 1.787s | -199ms | -10.02
| ChannelStore.CreateDirectChannel | p99 | 990ms | 912ms | -78ms | -7.88
| UserStore.GetMany | p99 | 94ms | 88ms | -6ms | -6.36
| ChannelStore.UpdateLastViewedAt | p99 | 274ms | 259ms | -15ms | -5.47
| ThreadStore.MaintainMembership | p99 | 389ms | 368ms | -21ms | -5.39
| PostStore.GetPostIdBeforeTime | p99 | 214ms | 203ms | -11ms | -5.15
| ChannelStore.CreateInitialSidebarCategories | p99 | 908ms | 862ms | -46ms | -5.07
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 189ms | 180ms | -9ms | -4.77
| PreferenceStore.Save | p99 | 455ms | 434ms | -21ms | -4.62
| PostStore.AnalyticsPostCount | p99 | 10s | 9.7s | -300ms | -3.00
| AuditStore.Save | p99 | 215ms | 210ms | -5ms | -2.33
| ReactionStore.Save | p99 | 476ms | 466ms | -10ms | -2.10
| ThreadStore.MarkAllAsReadByChannels | p99 | 215ms | 211ms | -4ms | -1.86
| StatusStore.UpdateLastActivityAt | p99 | 217ms | 213ms | -4ms | -1.84
| ClusterDiscoveryStore.SetLastPingAt | p99 | 220ms | 216ms | -4ms | -1.82
| ThreadStore.MarkAllAsReadByTeam | p99 | 237ms | 233ms | -4ms | -1.68
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 186ms | 183ms | -3ms | -1.61
| UserStore.Update | p99 | 396ms | 390ms | -6ms | -1.52
| UserStore.Save | p99 | 484ms | 479ms | -5ms | -1.03
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 1.025s | 1.353s | 328ms | 31.99
| removeUserCustomStatus | avg | 516ms | 622ms | 106ms | 20.56
| updatePreferences | avg | 79ms | 94ms | 15ms | 18.93
| updateUserCustomStatus | avg | 634ms | 752ms | 118ms | 18.60
| logout | avg | 352ms | 403ms | 51ms | 14.49
| createDirectChannel | avg | 930ms | 1.049s | 119ms | 12.80
| uploadFileStream | avg | 658ms | 685ms | 27ms | 4.10
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getUserStatus | p99 | 5ms | 21ms | 16ms | 321.26
| logout | p99 | 2.078s | 2.256s | 178ms | 8.57
| createDirectChannel | p99 | 4.251s | 4.55s | 299ms | 7.03
| removeUserCustomStatus | p99 | 2.35s | 2.419s | 69ms | 2.94
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 36ms | 0s | -36ms | -101.11
| updateViewedProductNotices | avg | 97ms | 0s | -97ms | -100.50
| getGroupsAssociatedToChannelsByTeam | avg | 106ms | 0s | -106ms | -100.42
| getPrevTrialLicense | avg | 41ms | 0s | -41ms | -100.37
| handleCheckCWSConnection | avg | 89ms | 0s | -89ms | -100.26
| getTopDMsForUserSince | avg | 161ms | 0s | -161ms | -100.20
| getDrafts | avg | 100ms | 0s | -100ms | -100.14
| getTopChannelsForUserSince | avg | 253ms | 0s | -253ms | -100.07
| deleteDraft | avg | 41ms | 0s | -41ms | -100.05
| getTopInactiveChannelsForUserSince | avg | 1.52s | 0s | -1.52s | -100.03
| getTopReactionsForUserSince | avg | 3.992s | 0s | -3.992s | -100.00
| getChannelByNameForTeamName | avg | 602ms | 0s | -602ms | -100.00
| getTopReactionsForTeamSince | avg | 19.933s | 0s | -19.933s | -100.00
| acknowledgePost | avg | 188ms | 0s | -188ms | -100.00
| getTopChannelsForTeamSince | avg | 29.544s | 0s | -29.544s | -100.00
| searchFilesInTeam | avg | 288ms | 0s | -288ms | -99.97
| getFilteredUsersStats | avg | 348ms | 0s | -348ms | -99.95
| getAnalytics | avg | 569ms | 0s | -569ms | -99.92
| getProductNotices | avg | 133ms | 0s | -133ms | -99.91
| getTotalUsersStats | avg | 108ms | 0s | -108ms | -99.76
| getJobsByType | avg | 102ms | 0s | -102ms | -99.67
| getGroups | avg | 65ms | 0s | -65ms | -99.67
| getRolesByNames | avg | 22ms | 0s | -22ms | -98.92
| getTopThreadsForTeamSince | avg | 1.975s | 41ms | -1.934s | -97.93
| getTopThreadsForUserSince | avg | 617ms | 44ms | -573ms | -92.83
| getClientConfig | avg | 272ms | 30ms | -242ms | -88.88
| getTeamsUnreadForUser | avg | 118ms | 20ms | -98ms | -83.25
| getChannelsForTeamForUser | avg | 94ms | 17ms | -77ms | -81.90
| getChannelMembersForTeamForUser | avg | 88ms | 19ms | -69ms | -78.31
| getTeamsForUser | avg | 49ms | 11ms | -38ms | -78.22
| getPreferences | avg | 86ms | 20ms | -66ms | -76.66
| getUser | avg | 78ms | 21ms | -57ms | -72.90
| getAllTeams | avg | 61ms | 17ms | -44ms | -71.98
| searchAllChannels | avg | 527ms | 151ms | -376ms | -71.30
| getThreadsForUser | avg | 107ms | 32ms | -75ms | -69.94
| getPublicChannelsForTeam | avg | 123ms | 38ms | -85ms | -68.95
| createChannel | avg | 175ms | 56ms | -119ms | -67.81
| getChannel | avg | 177ms | 57ms | -120ms | -67.79
| getChannelStats | avg | 173ms | 63ms | -110ms | -63.69
| autocompleteUsers | avg | 457ms | 169ms | -288ms | -63.02
| getCategoriesForTeamForUser | avg | 220ms | 82ms | -138ms | -62.63
| getPostsForChannelAroundLastUnread | avg | 657ms | 259ms | -398ms | -60.59
| searchGroupChannels | avg | 104ms | 43ms | -61ms | -58.90
| getPostThread | avg | 463ms | 192ms | -271ms | -58.50
| searchUsers | avg | 258ms | 112ms | -146ms | -56.59
| gqlWebCurrentUserInfo | avg | 444ms | 196ms | -248ms | -55.82
| gqlWebChannelsAndChannelMembers | avg | 502ms | 225ms | -277ms | -55.17
| searchPostsInTeam | avg | 629ms | 285ms | -344ms | -54.73
| getChannelMembers | avg | 123ms | 56ms | -67ms | -54.34
| getUsersByNames | avg | 81ms | 38ms | -43ms | -53.32
| setPostReminder | avg | 506ms | 245ms | -261ms | -51.57
| getChannelsForUser | avg | 86ms | 42ms | -44ms | -50.91
| getChannelUnread | avg | 101ms | 50ms | -51ms | -50.42
| createUser | avg | 500ms | 258ms | -242ms | -48.43
| getTeamMembersForUser | avg | 52ms | 27ms | -25ms | -47.67
| autocompleteChannelsForTeamForSearch | avg | 509ms | 269ms | -240ms | -47.12
| viewChannel | avg | 395ms | 216ms | -179ms | -45.32
| getChannelMember | avg | 65ms | 37ms | -28ms | -42.77
| updateReadStateThreadByUser | avg | 666ms | 382ms | -284ms | -42.65
| addChannelMember | avg | 1.472s | 863ms | -609ms | -41.37
| getUsers | avg | 147ms | 88ms | -59ms | -40.16
| deletePost | avg | 418ms | 258ms | -160ms | -38.25
| saveReaction | avg | 275ms | 171ms | -104ms | -37.88
| followThreadByUser | avg | 236ms | 151ms | -85ms | -36.05
| getFileThumbnail | avg | 159ms | 105ms | -54ms | -33.97
| getFilePreview | avg | 171ms | 114ms | -57ms | -33.24
| getPostsForChannel | avg | 2s | 1.439s | -561ms | -28.06
| login | avg | 573ms | 416ms | -157ms | -27.40
| addTeamMember | avg | 3.47s | 2.606s | -864ms | -24.90
| updateCategoriesForTeamForUser | avg | 716ms | 549ms | -167ms | -23.33
| updateReadStateAllThreadsByUser | avg | 30ms | 23ms | -7ms | -23.23
| getProfileImage | avg | 94ms | 75ms | -19ms | -20.28
| createPost | avg | 2.515s | 2.108s | -407ms | -16.18
| unfollowThreadByUser | avg | 174ms | 164ms | -10ms | -5.76
| createCategoryForTeamForUser | avg | 250ms | 239ms | -11ms | -4.40
| createGroupChannel | avg | 1.782s | 1.733s | -49ms | -2.75
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| updateViewedProductNotices | p99 | 100ms | 0s | -100ms | -100.50
| getRolesByNames | p99 | 99ms | 0s | -99ms | -100.22
| handleCheckCWSConnection | p99 | 246ms | 0s | -246ms | -100.20
| getDrafts | p99 | 248ms | 0s | -248ms | -100.20
| getGroups | p99 | 246ms | 0s | -246ms | -100.16
| getProductNotices | p99 | 248ms | 0s | -248ms | -100.10
| searchFilesInTeam | p99 | 498ms | 0s | -498ms | -100.10
| getFilteredUsersStats | p99 | 978ms | 0s | -978ms | -100.05
| getTopDMsForUserSince | p99 | 1.663s | 0s | -1.663s | -100.03
| acknowledgePost | p99 | 1.393s | 0s | -1.393s | -100.01
| getTopInactiveChannelsForUserSince | p99 | 4.864s | 0s | -4.864s | -100.00
| getTopReactionsForUserSince | p99 | 9.798s | 0s | -9.798s | -100.00
| getTopChannelsForUserSince | p99 | 2.445s | 0s | -2.445s | -100.00
| getChannelByNameForTeamName | p99 | 995ms | 0s | -995ms | -100.00
| getTopReactionsForTeamSince | p99 | 10s | 0s | -10s | -100.00
| getTopChannelsForTeamSince | p99 | 10s | 0s | -10s | -100.00
| getPrevTrialLicense | p99 | 232ms | 0s | -232ms | -100.00
| getAnalytics | p99 | 2.413s | 0s | -2.413s | -100.00
| getJobsByType | p99 | 486ms | 0s | -486ms | -99.95
| channelMemberCountsByGroup | p99 | 248ms | 0s | -248ms | -99.90
| getGroupsAssociatedToChannelsByTeam | p99 | 246ms | 0s | -246ms | -99.85
| getTotalUsersStats | p99 | 248ms | 0s | -248ms | -99.80
| deleteDraft | p99 | 239ms | 0s | -239ms | -99.79
| getTopThreadsForTeamSince | p99 | 9.713s | 495ms | -9.218s | -94.90
| getTopThreadsForUserSince | p99 | 5.363s | 411ms | -4.952s | -92.34
| getTeamsUnreadForUser | p99 | 1.629s | 325ms | -1.304s | -80.06
| createUser | p99 | 9.197s | 1.972s | -7.225s | -78.56
| getClientConfig | p99 | 1.308s | 327ms | -981ms | -74.98
| getChannelsForTeamForUser | p99 | 922ms | 250ms | -672ms | -72.87
| getPreferences | p99 | 860ms | 248ms | -612ms | -71.14
| getChannelMembersForTeamForUser | p99 | 920ms | 282ms | -638ms | -69.33
| getChannel | p99 | 1.918s | 590ms | -1.328s | -69.24
| getAllTeams | p99 | 731ms | 246ms | -485ms | -66.37
| getChannelMembers | p99 | 1.388s | 492ms | -896ms | -64.57
| searchUsers | p99 | 2.061s | 741ms | -1.32s | -64.05
| getChannelStats | p99 | 2.084s | 781ms | -1.303s | -62.51
| searchAllChannels | p99 | 4.658s | 1.796s | -2.862s | -61.45
| getTeamsForUser | p99 | 497ms | 196ms | -301ms | -60.55
| autocompleteUsers | p99 | 2.378s | 941ms | -1.437s | -60.44
| getCategoriesForTeamForUser | p99 | 2.247s | 906ms | -1.341s | -59.69
| setPostReminder | p99 | 4.933s | 2.133s | -2.8s | -56.76
| getThreadsForUser | p99 | 986ms | 434ms | -552ms | -55.99
| getUser | p99 | 877ms | 388ms | -489ms | -55.77
| getPublicChannelsForTeam | p99 | 972ms | 434ms | -538ms | -55.34
| saveReaction | p99 | 2.206s | 988ms | -1.218s | -55.21
| followThreadByUser | p99 | 2.137s | 974ms | -1.163s | -54.43
| getPostsForChannelAroundLastUnread | p99 | 7.548s | 3.495s | -4.053s | -53.70
| searchGroupChannels | p99 | 960ms | 454ms | -506ms | -52.69
| gqlWebChannelsAndChannelMembers | p99 | 4.627s | 2.226s | -2.401s | -51.89
| createChannel | p99 | 985ms | 485ms | -500ms | -50.77
| searchPostsInTeam | p99 | 9.569s | 4.741s | -4.828s | -50.46
| getChannelsForUser | p99 | 928ms | 461ms | -467ms | -50.34
| getUsersByNames | p99 | 869ms | 432ms | -437ms | -50.29
| updateReadStateThreadByUser | p99 | 4.683s | 2.431s | -2.252s | -48.09
| getPostThread | p99 | 3.841s | 2.018s | -1.823s | -47.46
| getUsers | p99 | 1.676s | 887ms | -789ms | -47.09
| getChannelMember | p99 | 742ms | 394ms | -348ms | -46.92
| gqlWebCurrentUserInfo | p99 | 2.865s | 1.655s | -1.21s | -42.23
| getTeamMembersForUser | p99 | 644ms | 376ms | -268ms | -41.64
| addChannelMember | p99 | 8.171s | 4.824s | -3.347s | -40.96
| deletePost | p99 | 3.425s | 2.025s | -1.4s | -40.88
| getChannelUnread | p99 | 981ms | 580ms | -401ms | -40.86
| getFilePreview | p99 | 1.345s | 809ms | -536ms | -39.86
| getFileThumbnail | p99 | 1.29s | 794ms | -496ms | -38.44
| autocompleteChannelsForTeamForSearch | p99 | 3.72s | 2.294s | -1.426s | -38.34
| viewChannel | p99 | 3.233s | 2.013s | -1.22s | -37.73
| createCategoryForTeamForUser | p99 | 1.882s | 1.19s | -692ms | -36.77
| patchPost | p99 | 5.068s | 3.233s | -1.835s | -36.21
| unfollowThreadByUser | p99 | 1.37s | 966ms | -404ms | -29.48
| updateCategoriesForTeamForUser | p99 | 4.243s | 3.025s | -1.218s | -28.71
| login | p99 | 3.115s | 2.47s | -645ms | -20.71
| getProfileImage | p99 | 498ms | 457ms | -41ms | -8.24
| getUsersByIds | p99 | 179ms | 167ms | -12ms | -6.70
| updateReadStateAllThreadsByUser | p99 | 238ms | 223ms | -15ms | -6.29
| createPost | p99 | 9.943s | 9.497s | -446ms | -4.49
| createGroupChannel | p99 | 7.859s | 7.639s | -220ms | -2.80
| getUserStatusesByIds | p99 | 229ms | 223ms | -6ms | -2.62
| updatePreferences | p99 | 492ms | 483ms | -9ms | -1.83
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 20ms| 21ms | 1ms | 5.010
| |  P99| 215ms| 210ms | -5ms | -2.328
| BotStore.Get |  Avg| 43ms| 30ms | -13ms | -30.274
| |  P99| 382ms| 400ms | 18ms | 4.706
| BotStore.Save |  Avg| 4ms| 0s | -4ms | -105.771
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 873ms| 0s | -873ms | -100.017
| |  P99| 2.939s| 0s | -2.939s | -100.006
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 17ms| 19ms | 2ms | 12.116
| |  P99| 186ms| 183ms | -3ms | -1.613
| ChannelStore.AnalyticsTypeCount |  Avg| 380ms| 0s | -380ms | -99.891
| |  P99| 978ms| 0s | -978ms | -100.050
| ChannelStore.Autocomplete |  Avg| 494ms| 149ms | -345ms | -69.874
| |  P99| 4.651s| 1.782s | -2.869s | -61.683
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 509ms| 268ms | -241ms | -47.357
| |  P99| 3.72s| 2.294s | -1.426s | -38.335
| ChannelStore.CreateDirectChannel |  Avg| 167ms| 145ms | -22ms | -13.192
| |  P99| 990ms| 912ms | -78ms | -7.876
| ChannelStore.CreateInitialSidebarCategories |  Avg| 100ms| 87ms | -13ms | -12.964
| |  P99| 908ms| 862ms | -46ms | -5.066
| ChannelStore.CreateSidebarCategory |  Avg| 145ms| 192ms | 47ms | 32.315
| |  P99| 928ms| 962ms | 34ms | 3.665
| ChannelStore.Get |  Avg| 17ms| 3ms | -14ms | -82.517
| |  P99| 370ms| 87ms | -283ms | -76.486
| ChannelStore.GetAllChannelMembersForUser |  Avg| 25ms| 11ms | -14ms | -57.094
| |  P99| 440ms| 218ms | -222ms | -50.451
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 36ms| 63ms | 27ms | 76.035
| |  P99| 393ms| 478ms | 85ms | 21.654
| ChannelStore.GetByName |  Avg| 53ms| 25ms | -28ms | -53.203
| |  P99| 625ms| 334ms | -291ms | -46.552
| ChannelStore.GetByNameIncludeDeleted |  Avg| 102ms| 0s | -102ms | -100.373
| |  P99| 244ms| 0s | -244ms | -100.000
| ChannelStore.GetChannelUnread |  Avg| 78ms| 41ms | -37ms | -47.252
| |  P99| 864ms| 455ms | -409ms | -47.342
| ChannelStore.GetChannels |  Avg| 93ms| 29ms | -64ms | -68.570
| |  P99| 923ms| 383ms | -540ms | -58.500
| ChannelStore.GetChannelsByUser |  Avg| 86ms| 42ms | -44ms | -51.174
| |  P99| 926ms| 457ms | -469ms | -50.669
| ChannelStore.GetChannelsWithCursor |  Avg| 102ms| 45ms | -57ms | -55.792
| |  P99| 985ms| 466ms | -519ms | -52.678
| ChannelStore.GetFileCount |  Avg| 179ms| 30ms | -149ms | -83.139
| |  P99| 1s| 310ms | -690ms | -69.013
| ChannelStore.GetGuestCount |  Avg| 32ms| 10ms | -22ms | -68.694
| |  P99| 484ms| 208ms | -276ms | -57.021
| ChannelStore.GetMany |  Avg| 67ms| 27ms | -40ms | -59.321
| |  P99| 865ms| 364ms | -501ms | -57.889
| ChannelStore.GetMember |  Avg| 38ms| 13ms | -25ms | -65.469
| |  P99| 494ms| 213ms | -281ms | -56.844
| ChannelStore.GetMemberCount |  Avg| 83ms| 33ms | -50ms | -60.564
| |  P99| 940ms| 428ms | -512ms | -54.491
| ChannelStore.GetMemberCountsByGroup |  Avg| 32ms| 0s | -32ms | -99.626
| |  P99| 242ms| 0s | -242ms | -99.846
| ChannelStore.GetMemberForPost |  Avg| 55ms| 28ms | -27ms | -49.382
| |  P99| 625ms| 326ms | -299ms | -47.821
| ChannelStore.GetMembers |  Avg| 121ms| 110ms | -11ms | -9.112
| |  P99| 1.494s| 1.589s | 95ms | 6.359
| ChannelStore.GetMembersForUser |  Avg| 87ms| 33ms | -54ms | -61.833
| |  P99| 919ms| 408ms | -511ms | -55.627
| ChannelStore.GetMembersForUserWithCursor |  Avg| 104ms| 48ms | -56ms | -53.801
| |  P99| 986ms| 477ms | -509ms | -51.622
| ChannelStore.GetMembersForUserWithPagination |  Avg| 126ms| 0s | -126ms | -100.383
| |  P99| 448ms| 0s | -448ms | -100.111
| ChannelStore.GetMembersInfoByChannelIds |  Avg| 100ms| 41ms | -59ms | -59.069
| |  P99| 982ms| 438ms | -544ms | -55.406
| ChannelStore.GetPinnedPostCount |  Avg| 44ms| 15ms | -29ms | -65.987
| |  P99| 611ms| 238ms | -373ms | -61.018
| ChannelStore.GetPublicChannelsForTeam |  Avg| 121ms| 57ms | -64ms | -53.006
| |  P99| 969ms| 477ms | -492ms | -50.749
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 220ms| 81ms | -139ms | -63.264
| |  P99| 2.244s| 905ms | -1.339s | -59.660
| ChannelStore.GetSidebarCategory |  Avg| 147ms| 89ms | -58ms | -39.348
| |  P99| 1.478s| 754ms | -724ms | -48.974
| ChannelStore.GetTeamChannels |  Avg| 175ms| 88ms | -87ms | -49.760
| |  P99| 978ms| 615ms | -363ms | -37.115
| ChannelStore.GetTopChannelsForTeamSince |  Avg| 29.239s| 0s | -29.239s | -100.000
| |  P99| 10s| 0s | -10s | -100.000
| ChannelStore.GetTopChannelsForUserSince |  Avg| 92ms| 0s | -92ms | -99.480
| |  P99| 1.127s| 0s | -1.127s | -99.956
| ChannelStore.GetTopInactiveChannelsForUserSince |  Avg| 1.448s| 0s | -1.448s | -99.971
| |  P99| 4.747s| 0s | -4.747s | -100.001
| ChannelStore.IncrementMentionCount |  Avg| 17ms| 20ms | 3ms | 18.125
| |  P99| 201ms| 210ms | 9ms | 4.489
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannel |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateGuestCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateMemberCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidatePinnedPostCount |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.PostCountsByDuration |  Avg| 184ms| 0s | -184ms | -99.822
| |  P99| 2.088s| 0s | -2.088s | -100.024
| ChannelStore.Save |  Avg| 147ms| 104ms | -43ms | -29.186
| |  P99| 989ms| 739ms | -250ms | -25.290
| ChannelStore.SaveMember |  Avg| 193ms| 119ms | -74ms | -38.386
| |  P99| 1.819s| 936ms | -883ms | -48.531
| ChannelStore.SearchGroupChannels |  Avg| 103ms| 42ms | -61ms | -59.093
| |  P99| 960ms| 447ms | -513ms | -53.414
| ChannelStore.UpdateLastViewedAt |  Avg| 35ms| 42ms | 7ms | 19.729
| |  P99| 274ms| 259ms | -15ms | -5.470
| ChannelStore.UpdateSidebarCategories |  Avg| 340ms| 335ms | -5ms | -1.471
| |  P99| 2.314s| 2.39s | 76ms | 3.284
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 16ms| 21ms | 5ms | 30.523
| |  P99| 189ms| 180ms | -9ms | -4.773
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 26ms| 30ms | 4ms | 15.500
| |  P99| 220ms| 216ms | -4ms | -1.817
| CommandStore.AnalyticsCommandCount |  Avg| 121ms| 0s | -121ms | -100.078
| |  P99| 248ms| 0s | -248ms | -100.101
| CommandWebhookStore.Cleanup |  Avg| 37ms| 12ms | -25ms | -68.437
| |  P99| 241ms| 49ms | -192ms | -79.668
| ComplianceStore.MessageExport |  Avg| 349ms| 0s | -349ms | -100.141
| |  P99| 970ms| 0s | -970ms | -100.000
| DraftStore.Get |  Avg| 58ms| 0s | -58ms | -99.607
| |  P99| 244ms| 0s | -244ms | -100.000
| DraftStore.GetDraftsForUser |  Avg| 100ms| 0s | -100ms | -100.230
| |  P99| 248ms| 0s | -248ms | -100.202
| EmojiStore.GetMultipleByName |  Avg| 56ms| 26ms | -30ms | -53.954
| |  P99| 746ms| 342ms | -404ms | -54.125
| FileInfoStore.AttachToPost |  Avg| 30ms| 48ms | 18ms | 59.961
| |  P99| 244ms| 353ms | 109ms | 44.650
| FileInfoStore.DeleteForPost |  Avg| 21ms| 47ms | 26ms | 123.129
| |  P99| 96ms| 99ms | 3ms | 3.125
| FileInfoStore.Get |  Avg| 59ms| 31ms | -28ms | -47.488
| |  P99| 667ms| 366ms | -301ms | -45.152
| FileInfoStore.GetForPost |  Avg| 1ms| 0s | -1ms | -119.221
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.InvalidateFileInfosForPostCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 25ms| 34ms | 9ms | 36.184
| |  P99| 231ms| 240ms | 9ms | 3.900
| FileInfoStore.Search |  Avg| 109ms| 0s | -109ms | -99.902
| |  P99| 249ms| 0s | -249ms | -100.201
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 62ms| 27ms | -35ms | -56.352
| |  P99| 776ms| 358ms | -418ms | -53.891
| GroupStore.GetByName |  Avg| 32ms| 16ms | -16ms | -50.730
| |  P99| 413ms| 234ms | -179ms | -43.300
| GroupStore.GetGroups |  Avg| 74ms| 33ms | -41ms | -55.779
| |  P99| 856ms| 388ms | -468ms | -54.645
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 105ms| 0s | -105ms | -99.528
| |  P99| 246ms| 0s | -246ms | -99.846
| JobStore.Get |  Avg| 155ms| 30ms | -125ms | -80.694
| |  P99| 2.102s| 300ms | -1.802s | -85.741
| JobStore.GetAllByStatus |  Avg| 84ms| 40ms | -44ms | -52.262
| |  P99| 908ms| 444ms | -464ms | -51.113
| JobStore.GetAllByTypePage |  Avg| 102ms| 0s | -102ms | -99.847
| |  P99| 486ms| 0s | -486ms | -99.945
| JobStore.GetCountByStatusAndType |  Avg| 103ms| 33ms | -70ms | -68.242
| |  P99| 1.33s| 249ms | -1.081s | -81.278
| JobStore.GetNewestJobByStatusesAndType |  Avg| 104ms| 22ms | -82ms | -78.543
| |  P99| 885ms| 246ms | -639ms | -72.203
| JobStore.Save |  Avg| 31ms| 22ms | -9ms | -28.593
| |  P99| 235ms| 243ms | 8ms | 3.410
| JobStore.UpdateOptimistically |  Avg| 25ms| 26ms | 1ms | 3.994
| |  P99| 228ms| 190ms | -38ms | -16.648
| JobStore.UpdateStatus |  Avg| 16ms| 19ms | 3ms | 19.342
| |  P99| 190ms| 130ms | -60ms | -31.579
| JobStore.UpdateStatusOptimistically |  Avg| 17ms| 29ms | 12ms | 68.591
| |  P99| 90ms| 300ms | 210ms | 233.759
| LicenseStore.GetAll |  Avg| 40ms| 0s | -40ms | -99.423
| |  P99| 232ms| 0s | -232ms | -99.999
| LinkMetadataStore.Get |  Avg| 59ms| 26ms | -33ms | -55.759
| |  P99| 788ms| 351ms | -437ms | -55.438
| LinkMetadataStore.Save |  Avg| 15ms| 0s | -15ms | -100.734
| |  P99| 192ms| 0s | -192ms | -100.168
| PluginStore.Delete |  Avg| 12ms| 15ms | 3ms | 25.225
| |  P99| 152ms| 167ms | 15ms | 9.859
| PluginStore.Get |  Avg| 57ms| 22ms | -35ms | -61.026
| |  P99| 744ms| 293ms | -451ms | -60.611
| PluginStore.List |  Avg| 61ms| 26ms | -35ms | -57.623
| |  P99| 487ms| 219ms | -268ms | -55.080
| PluginStore.SetWithOptions |  Avg| 27ms| 32ms | 5ms | 18.523
| |  P99| 244ms| 246ms | 2ms | 0.819
| PostAcknowledgementStore.GetForPost |  Avg| 46ms| 0s | -46ms | -100.344
| |  P99| 463ms| 0s | -463ms | -99.902
| PostAcknowledgementStore.GetForPosts |  Avg| 45ms| 0s | -45ms | -100.118
| |  P99| 516ms| 0s | -516ms | -99.925
| PostAcknowledgementStore.Save |  Avg| 52ms| 0s | -52ms | -100.887
| |  P99| 412ms| 0s | -412ms | -99.943
| PostPriorityStore.GetForPost |  Avg| 45ms| 0s | -45ms | -100.653
| |  P99| 457ms| 0s | -457ms | -100.076
| PostPriorityStore.GetForPosts |  Avg| 45ms| 0s | -45ms | -99.189
| |  P99| 517ms| 0s | -517ms | -99.991
| PostStore.AnalyticsPostCount |  Avg| 7.854s| 3.38s | -4.474s | -56.967
| |  P99| 10s| 9.7s | -300ms | -3.000
| PostStore.Delete |  Avg| 166ms| 157ms | -9ms | -5.432
| |  P99| 1.587s| 941ms | -646ms | -40.693
| PostStore.Get |  Avg| 204ms| 92ms | -112ms | -55.034
| |  P99| 2.114s| 868ms | -1.246s | -58.939
| PostStore.GetEtag |  Avg| 40ms| 11ms | -29ms | -72.684
| |  P99| 573ms| 222ms | -351ms | -61.248
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 18ms| 18ms | 0s | 0.000
| |  P99| 207ms| 184ms | -23ms | -11.108
| PostStore.GetPostIdBeforeTime |  Avg| 19ms| 21ms | 2ms | 10.424
| |  P99| 214ms| 203ms | -11ms | -5.148
| PostStore.GetPostReminderMetadata |  Avg| 96ms| 34ms | -62ms | -64.672
| |  P99| 955ms| 311ms | -644ms | -67.435
| PostStore.GetPostReminders |  Avg| 40ms| 66ms | 26ms | 65.317
| |  P99| 387ms| 450ms | 63ms | 16.258
| PostStore.GetPosts |  Avg| 75ms| 31ms | -44ms | -58.719
| |  P99| 867ms| 364ms | -503ms | -58.033
| PostStore.GetPostsAfter |  Avg| 91ms| 40ms | -51ms | -56.006
| |  P99| 951ms| 443ms | -508ms | -53.394
| PostStore.GetPostsBefore |  Avg| 94ms| 44ms | -50ms | -53.037
| |  P99| 938ms| 455ms | -483ms | -51.515
| PostStore.GetPostsByThread |  Avg| 93ms| 37ms | -56ms | -60.405
| |  P99| 973ms| 423ms | -550ms | -56.500
| PostStore.GetPostsSince |  Avg| 136ms| 67ms | -69ms | -50.695
| |  P99| 984ms| 482ms | -502ms | -51.039
| PostStore.GetSingle |  Avg| 83ms| 30ms | -53ms | -64.167
| |  P99| 931ms| 385ms | -546ms | -58.653
| PostStore.GetTopDMsForUserSince |  Avg| 161ms| 0s | -161ms | -100.286
| |  P99| 1.663s| 0s | -1.663s | -100.030
| PostStore.HasAutoResponsePostByUserSince |  Avg| 88ms| 0s | -88ms | -99.452
| |  P99| 1.059s| 0s | -1.059s | -99.973
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 58ms| 73ms | 15ms | 25.710
| |  P99| 479ms| 496ms | 17ms | 3.549
| PostStore.SearchPostsForUser |  Avg| 223ms| 236ms | 13ms | 5.830
| |  P99| 1.7s| 1.452s | -248ms | -14.588
| PostStore.SetPostReminder |  Avg| 67ms| 73ms | 6ms | 9.012
| |  P99| 455ms| 459ms | 4ms | 0.879
| PostStore.Update |  Avg| 65ms| 84ms | 19ms | 29.378
| |  P99| 454ms| 463ms | 9ms | 1.984
| PreferenceStore.DeleteCategoryAndName |  Avg| 28ms| 40ms | 12ms | 43.505
| |  P99| 243ms| 355ms | 112ms | 46.155
| PreferenceStore.Get |  Avg| 75ms| 33ms | -42ms | -56.291
| |  P99| 876ms| 401ms | -475ms | -54.205
| PreferenceStore.GetAll |  Avg| 85ms| 20ms | -65ms | -76.494
| |  P99| 881ms| 248ms | -633ms | -71.835
| PreferenceStore.Save |  Avg| 58ms| 63ms | 5ms | 8.617
| |  P99| 455ms| 434ms | -21ms | -4.619
| ProductNoticesStore.ClearOldNotices |  Avg| 13ms| 15ms | 2ms | 15.855
| |  P99| 25ms| 49ms | 24ms | 96.864
| ProductNoticesStore.GetViews |  Avg| 133ms| 0s | -133ms | -100.238
| |  P99| 248ms| 0s | -248ms | -100.101
| ProductNoticesStore.View |  Avg| 92ms| 101ms | 9ms | 9.739
| |  P99| 834ms| 845ms | 11ms | 1.319
| ReactionStore.GetForPost |  Avg| 1ms| 0s | -1ms | -93.465
| |  P99| 5ms| 5ms | 0s | 0.000
| ReactionStore.GetTopForTeamSince |  Avg| 19.932s| 0s | -19.932s | -100.002
| |  P99| 10s| 0s | -10s | -100.000
| ReactionStore.GetTopForUserSince |  Avg| 3.923s| 0s | -3.923s | -100.004
| |  P99| 9.742s| 0s | -9.742s | -100.002
| ReactionStore.Save |  Avg| 67ms| 81ms | 14ms | 20.877
| |  P99| 476ms| 466ms | -10ms | -2.101
| RoleStore.ChannelHigherScopedPermissions |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.AnalyticsSessionCount |  Avg| 142ms| 0s | -142ms | -100.163
| |  P99| 248ms| 0s | -248ms | -100.101
| SessionStore.Get |  Avg| 38ms| 35ms | -3ms | -7.799
| |  P99| 393ms| 323ms | -70ms | -17.824
| SessionStore.GetSessionsExpired |  Avg| 43ms| 24ms | -19ms | -44.070
| |  P99| 455ms| 222ms | -233ms | -51.208
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 71ms| 30ms | -41ms | -57.545
| |  P99| 864ms| 353ms | -511ms | -59.111
| SessionStore.Remove |  Avg| 18ms| 24ms | 6ms | 32.499
| |  P99| 183ms| 204ms | 21ms | 11.466
| SessionStore.Save |  Avg| 89ms| 46ms | -43ms | -48.314
| |  P99| 897ms| 452ms | -445ms | -49.622
| SessionStore.UpdateLastActivityAt |  Avg| 20ms| 26ms | 6ms | 30.487
| |  P99| 203ms| 218ms | 15ms | 7.376
| StatusStore.Get |  Avg| 33ms| 15ms | -18ms | -54.833
| |  P99| 441ms| 238ms | -203ms | -45.984
| StatusStore.GetByIds |  Avg| 126ms| 52ms | -74ms | -58.809
| |  P99| 1.447s| 528ms | -919ms | -63.531
| StatusStore.SaveOrUpdate |  Avg| 87ms| 84ms | -3ms | -3.436
| |  P99| 1.986s| 1.787s | -199ms | -10.020
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 68ms| 56ms | -12ms | -17.597
| |  P99| 775ms| 240ms | -535ms | -69.032
| StatusStore.UpdateLastActivityAt |  Avg| 21ms| 25ms | 4ms | 18.898
| |  P99| 217ms| 213ms | -4ms | -1.843
| SystemStore.GetByName |  Avg| 19ms| 12ms | -7ms | -36.315
| |  P99| 218ms| 154ms | -64ms | -29.305
| TeamStore.AnalyticsTeamCount |  Avg| 35ms| 19ms | -16ms | -45.322
| |  P99| 459ms| 249ms | -210ms | -45.721
| TeamStore.Get |  Avg| 66ms| 27ms | -39ms | -58.742
| |  P99| 835ms| 358ms | -477ms | -57.160
| TeamStore.GetAllPage |  Avg| 58ms| 16ms | -42ms | -72.129
| |  P99| 709ms| 237ms | -472ms | -66.592
| TeamStore.GetByName |  Avg| 73ms| 33ms | -40ms | -54.579
| |  P99| 869ms| 438ms | -431ms | -49.576
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 69ms| 14ms | -55ms | -79.821
| |  P99| 824ms| 222ms | -602ms | -73.100
| TeamStore.GetMany |  Avg| 91ms| 43ms | -48ms | -52.497
| |  P99| 944ms| 450ms | -494ms | -52.348
| TeamStore.GetMember |  Avg| 64ms| 27ms | -37ms | -57.418
| |  P99| 782ms| 331ms | -451ms | -57.657
| TeamStore.GetTeamsByUserId |  Avg| 50ms| 11ms | -39ms | -78.775
| |  P99| 499ms| 191ms | -308ms | -61.678
| TeamStore.GetTeamsForUser |  Avg| 74ms| 32ms | -42ms | -56.999
| |  P99| 880ms| 410ms | -470ms | -53.382
| TeamStore.InvalidateAllTeamIdsForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.SaveMember |  Avg| 108ms| 157ms | 49ms | 45.286
| |  P99| 451ms| 744ms | 293ms | 64.946
| ThreadStore.Get |  Avg| 95ms| 38ms | -57ms | -60.268
| |  P99| 976ms| 422ms | -554ms | -56.769
| ThreadStore.GetMembershipForUser |  Avg| 73ms| 39ms | -34ms | -46.337
| |  P99| 866ms| 448ms | -418ms | -48.249
| ThreadStore.GetTeamsUnreadForUser |  Avg| 94ms| 28ms | -66ms | -69.959
| |  P99| 1s| 404ms | -596ms | -59.602
| ThreadStore.GetThreadFollowers |  Avg| 81ms| 36ms | -45ms | -55.843
| |  P99| 911ms| 440ms | -471ms | -51.715
| ThreadStore.GetThreadForUser |  Avg| 108ms| 52ms | -56ms | -52.042
| |  P99| 1.3s| 579ms | -721ms | -55.449
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 107ms| 41ms | -66ms | -61.402
| |  P99| 992ms| 451ms | -541ms | -54.561
| ThreadStore.GetThreadsForUser |  Avg| 104ms| 48ms | -56ms | -53.970
| |  P99| 963ms| 473ms | -490ms | -50.875
| ThreadStore.GetTopThreadsForTeamSince |  Avg| 1.383s| 0s | -1.383s | -100.027
| |  P99| 8.925s| 0s | -8.925s | -100.000
| ThreadStore.GetTopThreadsForUserSince |  Avg| 390ms| 0s | -390ms | -100.041
| |  P99| 4.704s| 0s | -4.704s | -99.996
| ThreadStore.GetTotalThreads |  Avg| 71ms| 31ms | -40ms | -56.554
| |  P99| 818ms| 411ms | -407ms | -49.754
| ThreadStore.GetTotalUnreadMentions |  Avg| 72ms| 30ms | -42ms | -58.613
| |  P99| 836ms| 404ms | -432ms | -51.705
| ThreadStore.GetTotalUnreadThreads |  Avg| 72ms| 31ms | -41ms | -56.987
| |  P99| 847ms| 406ms | -441ms | -52.053
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 41ms| 0s | -41ms | -100.913
| |  P99| 443ms| 0s | -443ms | -100.096
| ThreadStore.MaintainMembership |  Avg| 43ms| 51ms | 8ms | 18.666
| |  P99| 389ms| 368ms | -21ms | -5.393
| ThreadStore.MarkAllAsReadByChannels |  Avg| 20ms| 22ms | 2ms | 10.136
| |  P99| 215ms| 211ms | -4ms | -1.861
| ThreadStore.MarkAllAsReadByTeam |  Avg| 30ms| 34ms | 4ms | 13.506
| |  P99| 237ms| 233ms | -4ms | -1.685
| ThreadStore.MarkAsRead |  Avg| 18ms| 24ms | 6ms | 33.205
| |  P99| 178ms| 195ms | 17ms | 9.535
| ThreadStore.UpdateMembership |  Avg| 20ms| 25ms | 5ms | 24.770
| |  P99| 204ms| 203ms | -1ms | -0.491
| TokenStore.Cleanup |  Avg| 24ms| 12ms | -12ms | -49.981
| |  P99| 97ms| 49ms | -48ms | -49.485
| UserAccessTokenStore.GetByToken |  Avg| 85ms| 41ms | -44ms | -51.630
| |  P99| 897ms| 472ms | -425ms | -47.396
| UserStore.AnalyticsActiveCount |  Avg| 517ms| 0s | -517ms | -100.005
| |  P99| 987ms| 0s | -987ms | -99.985
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 99ms| 0s | -99ms | -99.780
| |  P99| 478ms| 0s | -478ms | -100.105
| UserStore.AutocompleteUsersInChannel |  Avg| 683ms| 301ms | -382ms | -55.889
| |  P99| 2.432s| 980ms | -1.452s | -59.700
| UserStore.Count |  Avg| 211ms| 100ms | -111ms | -52.643
| |  P99| 987ms| 390ms | -597ms | -60.517
| UserStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 47ms| 46ms | -1ms | -2.134
| UserStore.GetAllProfiles |  Avg| 82ms| 36ms | -46ms | -56.202
| |  P99| 916ms| 447ms | -469ms | -51.182
| UserStore.GetAllProfilesInChannel |  Avg| 817ms| 651ms | -166ms | -20.323
| |  P99| 4.822s| 3.986s | -836ms | -17.338
| UserStore.GetByUsername |  Avg| 93ms| 37ms | -56ms | -59.974
| |  P99| 977ms| 460ms | -517ms | -52.909
| UserStore.GetForLogin |  Avg| 66ms| 25ms | -41ms | -61.736
| |  P99| 788ms| 345ms | -443ms | -56.221
| UserStore.GetMany |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 94ms| 88ms | -6ms | -6.363
| UserStore.GetProfileByIds |  Avg| 4ms| 5ms | 1ms | 22.268
| |  P99| 136ms| 112ms | -24ms | -17.605
| UserStore.GetProfilesByUsernames |  Avg| 80ms| 37ms | -43ms | -53.885
| |  P99| 864ms| 423ms | -441ms | -51.017
| UserStore.GetProfilesInChannel |  Avg| 109ms| 54ms | -55ms | -50.361
| |  P99| 955ms| 495ms | -460ms | -48.151
| UserStore.GetUnreadCount |  Avg| 75ms| 33ms | -42ms | -55.809
| |  P99| 902ms| 355ms | -547ms | -60.619
| UserStore.GetUnreadCountForChannel |  Avg| 76ms| 33ms | -43ms | -56.513
| |  P99| 876ms| 391ms | -485ms | -55.381
| UserStore.InvalidateProfileCacheForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.InvalidateProfilesInChannelCacheByUser |  Avg| 295ms| 341ms | 46ms | 15.612
| |  P99| 1.961s| 2.228s | 267ms | 13.614
| UserStore.IsEmpty |  Avg| 20ms| 9ms | -11ms | -55.277
| |  P99| 317ms| 175ms | -142ms | -44.802
| UserStore.Save |  Avg| 111ms| 105ms | -6ms | -5.429
| |  P99| 484ms| 479ms | -5ms | -1.034
| UserStore.Search |  Avg| 253ms| 110ms | -143ms | -56.437
| |  P99| 2.046s| 728ms | -1.318s | -64.429
| UserStore.Update |  Avg| 48ms| 56ms | 8ms | 16.715
| |  P99| 396ms| 390ms | -6ms | -1.517
| UserStore.UpdateFailedPasswordAttempts |  Avg| 21ms| 23ms | 2ms | 9.478
| |  P99| 215ms| 219ms | 4ms | 1.860
| UserStore.UpdateUpdateAt |  Avg| 13ms| 14ms | 1ms | 7.796
| |  P99| 137ms| 146ms | 9ms | 6.566
| UserTermsOfServiceStore.GetByUser |  Avg| 93ms| 23ms | -70ms | -75.560
| |  P99| 952ms| 314ms | -638ms | -66.991
| WebhookStore.AnalyticsIncomingCount |  Avg| 128ms| 0s | -128ms | -100.078
| |  P99| 248ms| 0s | -248ms | -100.101
| WebhookStore.AnalyticsOutgoingCount |  Avg| 77ms| 0s | -77ms | -99.637
| |  P99| 246ms| 0s | -246ms | -100.204
| WebhookStore.GetOutgoingByTeam |  Avg| 80ms| 46ms | -34ms | -42.539
| |  P99| 885ms| 469ms | -416ms | -47.013
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
|  | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| acknowledgePost | Avg| 188ms| 0s | -188ms | -100.002
| | P99| 1.393s| 0s | -1.393s | -100.006
| addChannelMember | Avg| 1.472s| 863ms | -609ms | -41.367
| | P99| 8.171s| 4.824s | -3.347s | -40.961
| addTeamMember | Avg| 3.47s| 2.606s | -864ms | -24.901
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 509ms| 269ms | -240ms | -47.122
| | P99| 3.72s| 2.294s | -1.426s | -38.335
| autocompleteUsers | Avg| 457ms| 169ms | -288ms | -63.017
| | P99| 2.378s| 941ms | -1.437s | -60.438
| channelMemberCountsByGroup | Avg| 36ms| 0s | -36ms | -101.109
| | P99| 248ms| 0s | -248ms | -99.901
| createCategoryForTeamForUser | Avg| 250ms| 239ms | -11ms | -4.398
| | P99| 1.882s| 1.19s | -692ms | -36.769
| createChannel | Avg| 175ms| 56ms | -119ms | -67.810
| | P99| 985ms| 485ms | -500ms | -50.769
| createDirectChannel | Avg| 930ms| 1.049s | 119ms | 12.798
| | P99| 4.251s| 4.55s | 299ms | 7.033
| createGroupChannel | Avg| 1.782s| 1.733s | -49ms | -2.750
| | P99| 7.859s| 7.639s | -220ms | -2.799
| createPost | Avg| 2.515s| 2.108s | -407ms | -16.185
| | P99| 9.943s| 9.497s | -446ms | -4.486
| createUser | Avg| 500ms| 258ms | -242ms | -48.433
| | P99| 9.197s| 1.972s | -7.225s | -78.555
| deleteDraft | Avg| 41ms| 0s | -41ms | -100.053
| | P99| 239ms| 0s | -239ms | -99.791
| deletePost | Avg| 418ms| 258ms | -160ms | -38.246
| | P99| 3.425s| 2.025s | -1.4s | -40.876
| followThreadByUser | Avg| 236ms| 151ms | -85ms | -36.055
| | P99| 2.137s| 974ms | -1.163s | -54.426
| getAllTeams | Avg| 61ms| 17ms | -44ms | -71.978
| | P99| 731ms| 246ms | -485ms | -66.373
| getAnalytics | Avg| 569ms| 0s | -569ms | -99.920
| | P99| 2.413s| 0s | -2.413s | -99.996
| getCategoriesForTeamForUser | Avg| 220ms| 82ms | -138ms | -62.635
| | P99| 2.247s| 906ms | -1.341s | -59.692
| getChannel | Avg| 177ms| 57ms | -120ms | -67.787
| | P99| 1.918s| 590ms | -1.328s | -69.242
| getChannelByNameForTeamName | Avg| 602ms| 0s | -602ms | -100.004
| | P99| 995ms| 0s | -995ms | -100.000
| getChannelMember | Avg| 65ms| 37ms | -28ms | -42.775
| | P99| 742ms| 394ms | -348ms | -46.922
| getChannelMembers | Avg| 123ms| 56ms | -67ms | -54.340
| | P99| 1.388s| 492ms | -896ms | -64.573
| getChannelMembersForTeamForUser | Avg| 88ms| 19ms | -69ms | -78.307
| | P99| 920ms| 282ms | -638ms | -69.335
| getChannelStats | Avg| 173ms| 63ms | -110ms | -63.694
| | P99| 2.084s| 781ms | -1.303s | -62.513
| getChannelUnread | Avg| 101ms| 50ms | -51ms | -50.416
| | P99| 981ms| 580ms | -401ms | -40.862
| getChannelsForTeamForUser | Avg| 94ms| 17ms | -77ms | -81.901
| | P99| 922ms| 250ms | -672ms | -72.866
| getChannelsForUser | Avg| 86ms| 42ms | -44ms | -50.909
| | P99| 928ms| 461ms | -467ms | -50.343
| getClientConfig | Avg| 272ms| 30ms | -242ms | -88.878
| | P99| 1.308s| 327ms | -981ms | -74.983
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getDrafts | Avg| 100ms| 0s | -100ms | -100.140
| | P99| 248ms| 0s | -248ms | -100.202
| getFilePreview | Avg| 171ms| 114ms | -57ms | -33.240
| | P99| 1.345s| 809ms | -536ms | -39.865
| getFileThumbnail | Avg| 159ms| 105ms | -54ms | -33.970
| | P99| 1.29s| 794ms | -496ms | -38.437
| getFilteredUsersStats | Avg| 348ms| 0s | -348ms | -99.949
| | P99| 978ms| 0s | -978ms | -100.051
| getGroups | Avg| 65ms| 0s | -65ms | -99.666
| | P99| 246ms| 0s | -246ms | -100.164
| getGroupsAssociatedToChannelsByTeam | Avg| 106ms| 0s | -106ms | -100.416
| | P99| 246ms| 0s | -246ms | -99.846
| getJobsByType | Avg| 102ms| 0s | -102ms | -99.668
| | P99| 486ms| 0s | -486ms | -99.945
| getPostThread | Avg| 463ms| 192ms | -271ms | -58.505
| | P99| 3.841s| 2.018s | -1.823s | -47.459
| getPostsForChannel | Avg| 2s| 1.439s | -561ms | -28.055
| | P99| 10s| 10s | 0s | 0.000
| getPostsForChannelAroundLastUnread | Avg| 657ms| 259ms | -398ms | -60.588
| | P99| 7.548s| 3.495s | -4.053s | -53.697
| getPreferences | Avg| 86ms| 20ms | -66ms | -76.656
| | P99| 860ms| 248ms | -612ms | -71.144
| getPrevTrialLicense | Avg| 41ms| 0s | -41ms | -100.375
| | P99| 232ms| 0s | -232ms | -99.999
| getProductNotices | Avg| 133ms| 0s | -133ms | -99.911
| | P99| 248ms| 0s | -248ms | -100.101
| getProfileImage | Avg| 94ms| 75ms | -19ms | -20.284
| | P99| 498ms| 457ms | -41ms | -8.239
| getPublicChannelsForTeam | Avg| 123ms| 38ms | -85ms | -68.948
| | P99| 972ms| 434ms | -538ms | -55.343
| getRolesByNames | Avg| 22ms| 0s | -22ms | -98.915
| | P99| 99ms| 0s | -99ms | -100.221
| getTeamMembersForUser | Avg| 52ms| 27ms | -25ms | -47.670
| | P99| 644ms| 376ms | -268ms | -41.642
| getTeamsForUser | Avg| 49ms| 11ms | -38ms | -78.215
| | P99| 497ms| 196ms | -301ms | -60.555
| getTeamsUnreadForUser | Avg| 118ms| 20ms | -98ms | -83.254
| | P99| 1.629s| 325ms | -1.304s | -80.063
| getThreadsForUser | Avg| 107ms| 32ms | -75ms | -69.935
| | P99| 986ms| 434ms | -552ms | -55.986
| getTopChannelsForTeamSince | Avg| 29.544s| 0s | -29.544s | -100.001
| | P99| 10s| 0s | -10s | -100.000
| getTopChannelsForUserSince | Avg| 253ms| 0s | -253ms | -100.070
| | P99| 2.445s| 0s | -2.445s | -100.000
| getTopDMsForUserSince | Avg| 161ms| 0s | -161ms | -100.202
| | P99| 1.663s| 0s | -1.663s | -100.030
| getTopInactiveChannelsForUserSince | Avg| 1.52s| 0s | -1.52s | -100.028
| | P99| 4.864s| 0s | -4.864s | -100.001
| getTopReactionsForTeamSince | Avg| 19.933s| 0s | -19.933s | -100.002
| | P99| 10s| 0s | -10s | -100.000
| getTopReactionsForUserSince | Avg| 3.992s| 0s | -3.992s | -100.005
| | P99| 9.798s| 0s | -9.798s | -100.001
| getTopThreadsForTeamSince | Avg| 1.975s| 41ms | -1.934s | -97.935
| | P99| 9.713s| 495ms | -9.218s | -94.900
| getTopThreadsForUserSince | Avg| 617ms| 44ms | -573ms | -92.833
| | P99| 5.363s| 411ms | -4.952s | -92.345
| getTotalUsersStats | Avg| 108ms| 0s | -108ms | -99.760
| | P99| 248ms| 0s | -248ms | -99.799
| getUser | Avg| 78ms| 21ms | -57ms | -72.900
| | P99| 877ms| 388ms | -489ms | -55.772
| getUserStatus | Avg| 0s| 1ms | 1ms | 224.344
| | P99| 5ms| 21ms | 16ms | 321.256
| getUserStatusesByIds | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 229ms| 223ms | -6ms | -2.616
| getUsers | Avg| 147ms| 88ms | -59ms | -40.163
| | P99| 1.676s| 887ms | -789ms | -47.089
| getUsersByIds | Avg| 6ms| 7ms | 1ms | 16.396
| | P99| 179ms| 167ms | -12ms | -6.702
| getUsersByNames | Avg| 81ms| 38ms | -43ms | -53.323
| | P99| 869ms| 432ms | -437ms | -50.291
| getWebappPlugins | Avg| 1ms| 0s | -1ms | -119.106
| | P99| 6ms| 5ms | -1ms | -16.665
| gqlWebChannelsAndChannelMembers | Avg| 502ms| 225ms | -277ms | -55.170
| | P99| 4.627s| 2.226s | -2.401s | -51.894
| gqlWebCurrentUserInfo | Avg| 444ms| 196ms | -248ms | -55.816
| | P99| 2.865s| 1.655s | -1.21s | -42.234
| handleCheckCWSConnection | Avg| 89ms| 0s | -89ms | -100.257
| | P99| 246ms| 0s | -246ms | -100.203
| login | Avg| 573ms| 416ms | -157ms | -27.398
| | P99| 3.115s| 2.47s | -645ms | -20.707
| logout | Avg| 352ms| 403ms | 51ms | 14.489
| | P99| 2.078s| 2.256s | 178ms | 8.565
| patchPost | Avg| 1.025s| 1.353s | 328ms | 31.991
| | P99| 5.068s| 3.233s | -1.835s | -36.206
| removeUserCustomStatus | Avg| 516ms| 622ms | 106ms | 20.557
| | P99| 2.35s| 2.419s | 69ms | 2.936
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 275ms| 171ms | -104ms | -37.884
| | P99| 2.206s| 988ms | -1.218s | -55.212
| searchAllChannels | Avg| 527ms| 151ms | -376ms | -71.304
| | P99| 4.658s| 1.796s | -2.862s | -61.449
| searchFilesInTeam | Avg| 288ms| 0s | -288ms | -99.973
| | P99| 498ms| 0s | -498ms | -100.101
| searchGroupChannels | Avg| 104ms| 43ms | -61ms | -58.895
| | P99| 960ms| 454ms | -506ms | -52.685
| searchPostsInTeam | Avg| 629ms| 285ms | -344ms | -54.732
| | P99| 9.569s| 4.741s | -4.828s | -50.457
| searchUsers | Avg| 258ms| 112ms | -146ms | -56.588
| | P99| 2.061s| 741ms | -1.32s | -64.049
| setPostReminder | Avg| 506ms| 245ms | -261ms | -51.570
| | P99| 4.933s| 2.133s | -2.8s | -56.757
| unfollowThreadByUser | Avg| 174ms| 164ms | -10ms | -5.762
| | P99| 1.37s| 966ms | -404ms | -29.483
| updateCategoriesForTeamForUser | Avg| 716ms| 549ms | -167ms | -23.332
| | P99| 4.243s| 3.025s | -1.218s | -28.709
| updatePreferences | Avg| 79ms| 94ms | 15ms | 18.935
| | P99| 492ms| 483ms | -9ms | -1.830
| updateReadStateAllThreadsByUser | Avg| 30ms| 23ms | -7ms | -23.227
| | P99| 238ms| 223ms | -15ms | -6.294
| updateReadStateThreadByUser | Avg| 666ms| 382ms | -284ms | -42.650
| | P99| 4.683s| 2.431s | -2.252s | -48.091
| updateUserCustomStatus | Avg| 634ms| 752ms | 118ms | 18.600
| | P99| 2.471s| 2.463s | -8ms | -0.324
| updateViewedProductNotices | Avg| 97ms| 0s | -97ms | -100.501
| | P99| 100ms| 0s | -100ms | -100.503
| uploadFileStream | Avg| 658ms| 685ms | 27ms | 4.105
| | P99| 2.418s| 2.431s | 13ms | 0.538
| viewChannel | Avg| 395ms| 216ms | -179ms | -45.323
| | P99| 3.233s| 2.013s | -1.22s | -37.733
